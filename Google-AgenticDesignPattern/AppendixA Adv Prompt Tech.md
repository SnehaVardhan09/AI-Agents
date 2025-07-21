# Intro to prompting

## Prompting 
- process of crafting inputs to guide the model towards generating a desired ouput.
- structuring requests+ providing relevant context, specifying the output format, demonstrating expected response type 
- Objective : consistently elicit high-quality responses
- prompting techniques 
- Agentic patterns, the architectural structure for building intelligent systems.

## Core Prompting Principles
- Clarity and Specificity: Instruction should be unambiguous and precise. Define task, desired output format, and any limitations or requirements.
- Conciseness: Use direct phrasing and active verbs to clearly delineate the desired action. Effective verbs include: Act, Analyze, Categorize, Classify, Contrast, Compare, Create, Describe, Define, Evaluate, Extract, Fined, Generate, Identify, List, Measure, Organize, Parse, Pick, Predict, Provide, Rank, Recommend, Return, Retrieve, Rewrite, Select, show, Sort, Summarize, Translate, Write.
- Using Verbs: Action verbs indicate the expected operations
- Instructions Over Constrain
- Experimentation and Iteration : Model variations, Configurations (like temperature or top-p) and slight phrasing changes can yeild different results. Documenting attempts is bital for L&D.

## Basic Prompting Techniques

### Zero-shot Prompting
        - Provided with an instruction and input data without any examples of the desired input-output pair.
        - When to use: for tasks that the model has likely encountered extensively during its training, such as simple Q&A, text             Completion, or basic summarization of straight forward text.


### One-shot Prompting
        - Providing the LLM with a single example of the input and the corresponding desire output prior to presenting the actual task.
        - When to use: Useful when the desired output format or style is specific or less common.
        - Translation

### Few-shot Promptig
        - Few-shot prompting enhances one-shot prompting by supplying several examples, typically 3-5, on input-output pairs. This aims to demonstrate a clearer pattern of expected responses.
        