**Building AI Agents**

* Multi AI Agent - each agent with specific task and role - and these agents can collaborate to perform complex workflows.
* Key challenge is balancing speed and accuracy while maintaining consistency. 
* sequencial, parallel and hybrid running of multiple agents
* Mix and match multiple llm models based on the task at hand.


**Overview**

* Multi agentic Automation 
* Use Cases: Operations Automation, marketing, Code Development, Research, Education, Support, Other..
* **Existing Systems**
            |
  * Documents Internet CRM ERP ------> Research   |
  * Compare Extract Infer -----------> Analysis   | -> **existing systems**
  * Learninig Charts ExecuSummary----> Summary    |
  * PDF JSON Markdown ---------------> Reporting  | 

Not neccessarily these in series of steps. 


Regular Apps --> **Strong Types Inputs** ---------- Well-defined Transformations ---------- **Strong Typed Outputs**

AI Apps ---> **Fuzzy inputs**(text into **GPT**) -------- BLackBox --------- **Fuzzy Outputs**

LLM + Tools -- Initiallly they are simple. once we bring them to production setting, we are going to learn that additional layers are necessary like Caching, memory, train, Gaurdrails.....

* Sequential
* Hierarchial
* Hybrid
* Parallel
* Async

**Building Blocks**
[AGENTS(+tools) -> TASKS(+tools)] ========> Crew (guadrails, testing, delegation, training, memory)

1. Agents - ROLE + GOAL + BACKSTORY
2. Tasks - DESCRIPTION + EXPECTED OUTPUT + AGENT
