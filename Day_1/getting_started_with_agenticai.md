**What is Agentic AI?**

  * Agentic AI involves creating specialized software programs or "groups of code" called agents to handle specific tasks within a larger project, similar to a supervisor delegating tasks to a team.
  * It's a product of generative AI and is built upon Large Language Models (LLMs) which serve as the "brain."
  * Agentic AI automates much of the process, reducing human effort to about 20% (mainly for starting the process and final analysis), compared to 80% in traditional AI.
  * Agents are goal-oriented, work independently, can perform complex tasks sequentially, adapt to changing conditions, and correct errors.

**Characteristics of AI Agents:**

  * **Autonomy:** Works independently without constant human intervention.
  * **Perception:** Ability to see and sense its environment, read web pages, process data, and understand requests.
  * **Decision-making:** Good at making decisions.
  * **Concrete Actions:** Can perform actions like writing emails, executing code, clicking buttons, and generating reports.

**LLMs Explained:**

  * LLMs (like GPT and Claude) are trained on vast amounts of text data, converting words into numerical "vectors" in a vector database.
  * When a user queries an LLM, the natural language input is converted into a vector, which is then matched to the closest vector in the database to retrieve relevant information.

**AI Agent Workflow and Practical Application:**

  * The workflow involves receiving input, processing with the LLM, deciding the next step, and taking action.
  * A case study of building a travel planning agent was presented, showing how agents can set goals, search for information, analyze options, present plans, and refine them based on user input.
  * Complex tasks can be divided among multiple specialized agents.

**Tools for Developing AI Agents:**

  * **Flowise:** A primary open-source, low-code platform for building AI agents with a drag-and-drop interface, supporting multiple LLMs, and integration with various data sources. It offers a no-code approach compared to LangChain, which requires extensive coding. Agents created in Flowise can be tested, saved, duplicated, exported, and deployed via API endpoints.
  * Other tools mentioned include CrewAI, N8N, Autogen by Microsoft, Vector Sift, Voiceflow, Langraph, Stack AI, and Agency Swarm. The field is dynamic, and it's advised to become proficient in one tool before exploring others.

**Installation and Software Ecosystem:**

  * **Node.js:** Version 18, 19, or 20 is crucial for running Flowise.
  * **Flowise Installation:** Installed using Node Package Manager (npm) with the command `npm install -g flowise`.
  * **Starting Flowise:** Done using `npx flowise start`.
  * The meeting demonstrated accessing the Flowise interface via `localhost:3000`.

**Flowise Interface and Agent Building Blocks:**

  * The interface includes sections for chat flows, agent flows, executions, assistants, and a marketplace for pre-built agents.
  * The basic structure of an agent consists of a "supervisor" (main manager) and multiple "workers" (agents) to whom tasks are delegated.
  * LLMs power these agents, and tools (like web search or calculators) can be attached to enhance their capabilities.

**API Key Access and Agent Workflow Setup:**

  * Demonstrated how to access the API option in the dashboard to create a new API key (e.g., for Google Generative AI or OpenAI).
  * Detailed the process of setting up an agent (e.g., a story creator agent with a storyteller and a title creator).
  * A supervisor is crucial for sequential task execution to prevent random results from parallel processing.
  * Outlined prompts for workers (e.g., storyteller creates a short bedtime story, title creator provides ten engaging titles).
  * Configured the supervisor to ensure tasks are executed sequentially.

**Testing and Troubleshooting:**

  * Demonstrated testing the agent using a chat interface with a topic like "lion and deer."
  * When the initial Gemini model didn't work, it was explained how to switch to other models like OpenAI's GPT, highlighting that paid models generally offer more stable and reliable performance for agentic tasks.
  * Guided participants through generating and integrating an OpenAI API key.

**Successful Agent Operation and Performance Comparison:**

  * The agent successfully worked with the OpenAI model, showing sequential task execution.
  * Discussed the reliability of paid LLM services like OpenAI, noting smoother performance compared to free options like Gemini for agentic tasks.

**Open Source vs. Closed Source Tools and Local Hosting:**

  * Most AI agent tools are open-source, but the underlying language models can be either.
  * Using tools like Flowise in a local host environment allows for unlimited agent creation without payment, unlike cloud versions which often have free tiers with limitations.

**Suggested Next Steps:**

  * AI Council will try to build a travel agent practically.
  * The group will install NodeJS version 18, 19, or 20 on their system.
  * AI Council will upload the session recording tomorrow early.
