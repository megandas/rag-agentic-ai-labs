# Notebook 01 — Prompt Engineering & LCEL Cheat Sheet

## Important Terms

* Zero-shot Prompting — No examples provided.
* One-shot Prompting — One example provided.
* Few-shot Prompting — Multiple examples guide the model.
* Chain-of-Thought (CoT) — Step-by-step reasoning before the final answer.
* Self-Consistency — Generate multiple reasoning paths and choose the most consistent answer.
* PromptTemplate — Reusable prompt using variables in `{}`.
* ChatPromptTemplate — Prompt with System + Human messages.
* LCEL — LangChain Expression Language using the pipe (`|`) operator.
* RunnableLambda — Wraps a Python function as a runnable component.
* RunnableParallel — Executes multiple tasks concurrently on the same input.
* RunnableSequence — Sequential execution (LCEL replaces this with `|`).
* StrOutputParser — Converts LLM output into a plain string.
* Type Coercion — Function → RunnableLambda, Dictionary → RunnableParallel.

## Quiz One-Liners

* Few-shot prompting teaches the LLM the desired output pattern through examples.
* Chain-of-Thought prompting improves reasoning by generating intermediate steps.
* Prompt templates make prompts reusable with variables.
* LCEL creates readable pipelines using the pipe operator.
* RunnableParallel processes independent tasks simultaneously using one input.
* Type coercion automatically converts ordinary Python functions and dictionaries into runnable LangChain components.
