# How to Read a Research Paper Effortlessly with AI Tools: A Step-by-Step Guide

## Set Context and Role
### Prompt
- Act Like AI/ML Researcher and help me to understand Research Paper \<Name of the Paper>

## Initial Interaction: Summarizing the Research Paper
### Prompt:
- At first, I want an elaborate summary of the entire article. Return a bullet list with:
    - Main problem addressed
    - Core idea (3-4 sentences)  
    - Claimed contributions (short phrases)  

## Reading the Introduction
### Prompt
Summarize the Introduction section in ≤200 words. 
Highlight: 
- Practical or theoretical gap the authors claim, 
- Prior work they say is insufficient, 
- Specific real-world stakes (datasets, applications, societal impact).

## Get a high-level outline you can keep as a reference “table of contents.”
### Prompt
- Create a hierarchical outline of the paper. For every top-level section include a one-line purpose statement. For sub-sections, add a short note (~5 words) on what is done or proved there. Return in Markdown outline format.

## Breaking Down Complex Mathematical Concepts
### Prompt:
- Explain all the mathematical functions in the text to a under grad student.
Who knows basic deep learning, machine learning but not this technique. 
- Do NOT omit symbols: rewrite each equation, define every variable, and describe each step in plain language. 
- Where relevant, draw analogies to known models (e.g., Transformer, CNN). 
Use numbered steps for algorithm flow.

## Reproduce Pseudocodes
### Example Prompt
- Convert Algorithm 1 and Equation (3) into clean, runnable PyTorch pseudocode. Assume tensors x (batch, seq, d), W_q, W_k, W_v exist. 
Focus on clarity, variable shapes, and comments; skip training loop. 
Return ONLY the code block.

## Generating Better Questions
### Prompt
- When you are asked a question, suggest a better version of the question and ask me if I would like to use it instead.”

## Multiple Questions and combined Answer
### Prompt
- When you are asked a question, follow these rules Generate several additional questions that would help more accurately answer the question.
- Combine the answers to the individual questions to produce the final solution to the overall question.