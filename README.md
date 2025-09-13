# LangChain_RAGTool_ReActMultiAgent

ReAct Agent with Custom tools

## This Project consist of : 
- RAG tool
- ReAct
- custom tool with ReAct agent

## ReAct Agent (Reasoning + Acting):
## Definition:

The ReAct framework combines reasoning and acting in a single loop to handle tasks. The agent uses natural language reasoning (thinking through steps) and task actions (performing tasks like calculations or data retrieval).

The agent uses a combination of reasoning steps to guide actions in real-time, using feedback from those actions to further inform the next step in reasoning.

How it works:

Step 1: The agent receives a question or task.
Step 2: It reasons aloud (in natural language) about how to solve it.
Step 3: Based on its reasoning, it takes actions (e.g., searching a database, calculating something).
Step 4: The results of these actions are integrated into its reasoning and may trigger further actions.
Step 5: It repeats the process until it arrives at a solution.
Key points:

Combines thinking and doing (reasoning and actions).
Performs iterative steps, updating its process based on action results.
Typically handles complex decision-making scenarios.
