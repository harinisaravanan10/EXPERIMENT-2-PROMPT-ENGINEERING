# EXP-2-PROMPT-ENGINEERING-

## Aim: 
Comparative Analysis of different types of Prompting patterns and explain with Various Test Scenarios

Experiment:
Test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios. 
Analyze the quality, accuracy, and depth of the generated responses.


## Algorithm:
**1.Define Prompt Categories:**

Broad/Unstructured Prompt: A simple, open-ended question.

Refined/Structured Prompt: A prompt for the same task, but including specific instructions, context, and constraints.

**2.Select Test Scenarios:** Choose a variety of tasks that require different types of reasoning and knowledge.

Scenario 1: Factual Inquiry: A question about a historical event or scientific concept.

Scenario 2: Creative Writing: A request to generate a story or poem.

Scenario 3: Problem Solving: A task requiring logical reasoning, like a math word problem.

Scenario 4: Summarization: A request to summarize a provided text.

**3.Create Prompts for Each Scenario:** 
For each scenario, develop two prompts: one broad and one refined.

**4.Execute the Test:**

Input the broad prompt into the LLM and record the output.

Input the refined prompt into the LLM and record the output.

**5.Analyze and Score Responses:** Evaluate each output based on a predefined rubric. The rubric will assess:

Quality: Is the information accurate, relevant, and well-written?

Accuracy: How correct is the factual information? (Especially important for Factual Inquiry and Problem Solving).

Depth: Does the response provide a comprehensive and detailed answer, or is it superficial?

Adherence to Instructions: For the refined prompts, did the model follow all the instructions (e.g., tone, format, length)?

**6.Compare and Conclude:** Compare the scores of the broad and refined prompts for each scenario to draw conclusions about the effectiveness of each prompting pattern.

## Test Scenarios
**1.Scenario 1: Factual Inquiry**

Broad Prompt: Tell me about the causes of the French Revolution.

Refined Prompt: You are a history professor. Explain the main political, social, and economic causes of the French Revolution in a concise, bulleted list. Start with an introductory sentence and end with a concluding sentence. Do not exceed 200 words.

**2.Scenario 2: Creative Writing**

Broad Prompt: Write a short story about a person who finds a magical key.

Refined Prompt: Act as a fantasy author. Write a 2-paragraph short story about a cynical detective who finds a magical, rusty key that can unlock any door, but only once. The story should be set in a modern, rain-soaked city and have a mysterious, noir tone.

**3.Scenario 3: Problem Solving**

Broad Prompt: If a train travels at 60 mph and a car at 70 mph, which is faster?

Refined Prompt (Chain-of-Thought): Let's solve this step by step. A train travels at 60 mph. A car travels at 70 mph. Compare the two speeds. The final answer should be a single sentence that states which vehicle is faster and why.

**4.Scenario 4: Summarization**

Broad Prompt: Summarize the following text: "The development of renewable energy sources, such as solar and wind power, is crucial for mitigating climate change. These technologies reduce our reliance on fossil fuels, which are a major contributor to greenhouse gas emissions. While the initial cost of installation can be high, the long-term benefits include lower operating costs and a reduced environmental footprint. Governments and private companies are investing heavily in these sectors to accelerate the transition to a sustainable energy future. However, challenges remain in energy storage and grid integration, which must be addressed to ensure a stable and reliable power supply."

Refined Prompt: Summarize the following text for a high school student. The summary should be a 3-point bulleted list, highlighting the main argument and key challenges related to renewable energy. Text: "The development of renewable energy sources, such as solar and wind power, is crucial for mitigating climate change. These technologies reduce our reliance on fossil fuels, which are a major contributor to greenhouse gas emissions. While the initial cost of installation can be high, the long-term benefits include lower operating costs and a reduced environmental footprint. Governments and private companies are investing heavily in these sectors to accelerate the transition to a sustainable energy future. However, challenges remain in energy storage and grid integration, which must be addressed to ensure a stable and reliable power supply."

## Output
**Scenario 1: Factual Inquiry**

Broad Prompt Output: The French Revolution was a period of far-reaching social and political upheaval in France. It was caused by various factors, including the country's financial crisis, social inequality, and the influence of Enlightenment ideas. The monarchy was overthrown, and the republic was established. (General, lacks structure)

Refined Prompt Output: `The French Revolution was sparked by a combination of deep-seated issues.

Political: The absolute monarchy under King Louis XVI was inefficient and seen as tyrannical.

Social: French society was divided into three estates, with the Third Estate (commoners) bearing the tax burden while the nobility and clergy enjoyed privileges.

Economic: France was in a severe financial crisis due to costly wars and royal spending, exacerbated by poor harvests.
In conclusion, a confluence of these factors led to the widespread discontent that ultimately ignited the revolution.` (Clear, structured, adheres to persona and constraints)


## Result
<img width="830" height="586" alt="Screenshot 2025-08-30 130340" src="https://github.com/user-attachments/assets/a1474ffc-6822-43ce-84e1-b0de3ebcfb85" />

