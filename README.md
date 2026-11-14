# AI & LLM Testing Starter

Beginner-friendly examples of **testing an AI chatbot** using [Promptfoo](https://www.promptfoo.dev/), a free, open-source tool for evaluating LLM applications.

## What these tests check
| # | Test | What it checks |
|---|------|----------------|
| 1 | Accuracy | Does the AI give the correct facts? |
| 2 | Hallucination | Does it admit when it does not know, instead of inventing an answer? |
| 3 | Prompt injection | Can a user trick it into revealing its hidden instructions? |
| 4 | Staying on topic | Does it politely refuse unrelated requests? |

## How to run
1. Install Node.js
2. Set your AI provider API key (for example `OPENAI_API_KEY`)
3. Download `promptfooconfig.yaml` from this repository
4. Run: `npx promptfoo@latest eval`
5. See the results in your browser: `npx promptfoo@latest view`

## Why AI testing matters
AI answers change every time and can sound confident while being wrong. AI testers check accuracy, safety, bias and security before real users see the chatbot.

## Learn AI & LLM Testing live
This example is from [Isha Training Solutions](https://www.ishatrainingsolutions.org/). Our live online [AI & LLM Testing course](https://www.ishatrainingsolutions.org/courses/ai-llm-testing-from-beginner-to-master/) covers hallucination testing, prompt injection, RAG evaluation and AI testing tools with real-time projects. We also offer Claude certification, Generative & Agentic AI, FDE and Tosca training.
