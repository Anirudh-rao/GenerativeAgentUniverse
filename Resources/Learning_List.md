# 🧭 Generative AI, LLMs & AI Agents Roadmap (Python) — Free Resources

*A topic-wise path from basics to advanced, using only free/open resources. Last checked: September 2026.*

> **How to use this:** Go phase by phase. Don't skip Phase 1–2 even if you know some Python — the math/ML intuition pays off later. Budget ~4–6 months at 5–8 hrs/week for the full path.

---

## Phase 0: Prerequisites (1–2 weeks)

| Topic | Resource | Type |
|---|---|---|
| Python fundamentals | [CS50P – Harvard's Intro to Python](https://cs50.harvard.edu/python/) | Course (free, video+problem sets) |
| Python (alt/faster) | [Python Official Tutorial](https://docs.python.org/3/tutorial/) | Docs |
| Git & GitHub | [Git & GitHub Crash Course – freeCodeCamp](https://www.freecodecamp.org/news/git-and-github-for-beginners/) | Article/Video |
| Command line basics | [Missing Semester (MIT)](https://missing.csail.mit.edu/) | Course |

**Checkpoint:** You can write functions, use classes, handle files, use pip/venv, and push code to GitHub.

---

## Phase 1: Math & ML Foundations (2–3 weeks)

You don't need to master this before moving on — enough to understand *why* models behave the way they do.

| Topic | Resource |
|---|---|
| Linear algebra intuition | [3Blue1Brown – Essence of Linear Algebra](https://www.3blue1brown.com/topics/linear-algebra) |
| Probability & stats basics | [Khan Academy – Statistics & Probability](https://www.khanacademy.org/math/statistics-probability) |
| Core ML concepts | [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course) |
| Classic ML in Python | [Kaggle Learn – Intro to ML](https://www.kaggle.com/learn/intro-to-machine-learning) |

**Checkpoint:** You understand vectors/matrices at a high level, what training/loss/gradient descent mean, and can train a basic scikit-learn model.

---

## Phase 2: Deep Learning & Neural Network Basics (3–4 weeks)

| Topic | Resource |
|---|---|
| Deep learning fundamentals | [fast.ai – Practical Deep Learning for Coders](https://course.fast.ai/) |
| Neural nets from scratch (intuition) | [3Blue1Brown – Neural Networks series](https://www.3blue1brown.com/topics/neural-networks) |
| PyTorch basics | [PyTorch Official 60-Min Blitz](https://docs.pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html) |
| Andrew Ng's ML/DL intuition (audit free) | [DeepLearning.AI Deep Learning Specialization](https://www.deeplearning.ai/courses/deep-learning-specialization/) |

**Checkpoint:** You can explain what a neural network, backpropagation, and an embedding are, and train a simple model in PyTorch.

---

## Phase 3: NLP & the Transformer Architecture (2–3 weeks)

This is the conceptual core of all modern generative AI.

| Topic | Resource |
|---|---|
| NLP basics | [Hugging Face NLP Course – Ch. 1–3](https://huggingface.co/learn/nlp-course) |
| The Transformer, explained visually | [Jay Alammar – The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/) |
| Attention mechanism | [Jay Alammar – The Illustrated GPT-2](https://jalammar.github.io/illustrated-gpt2/) |
| Original paper (optional, for depth) | ["Attention Is All You Need" (arXiv)](https://arxiv.org/abs/1706.03762) |

**Checkpoint:** You can explain self-attention, tokens, and embeddings, and why transformers replaced RNNs.

---

## Phase 4: Generative AI & LLM Fundamentals (3–4 weeks)

| Topic | Resource |
|---|---|
| Gen AI overview (quick, certificate) | [Google – Introduction to Generative AI](https://www.cloudskillsboost.google/paths/118) |
| LLMs overview | [Google – Introduction to Large Language Models](https://www.cloudskillsboost.google/paths/118) |
| Full hands-on LLM course (12 chapters) | [Hugging Face LLM Course](https://huggingface.co/learn/llm-course) |
| Using LLM APIs, prompting basics | [DeepLearning.AI – ChatGPT Prompt Engineering for Developers](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/) |
| Prompt engineering deep dive | [Anthropic – Prompt Engineering Overview (docs)](https://docs.claude.com/en/docs/build-with-claude/prompt-engineering/overview) |
| Fine-tuning & PEFT/LoRA intro | [Hugging Face LLM Course – Fine-tuning chapters](https://huggingface.co/learn/llm-course) |
| End-to-end Gen AI curriculum (21 lessons) | [Microsoft – Generative AI for Beginners (GitHub)](https://github.com/microsoft/generative-ai-for-beginners) |

**Checkpoint:** You can call an LLM API from Python, write effective prompts, and explain fine-tuning vs. prompting vs. RAG.

---

## Phase 5: Retrieval-Augmented Generation (RAG) & Vector Databases (2 weeks)

| Topic | Resource |
|---|---|
| RAG concept + build one | [DeepLearning.AI – LangChain: Chat with Your Data](https://www.deeplearning.ai/short-courses/langchain-chat-with-your-data/) |
| Building multi-step LLM apps | [DeepLearning.AI – Building Systems with the ChatGPT API](https://www.deeplearning.ai/short-courses/building-systems-with-chatgpt/) |
| Vector databases | [Pinecone – Vector Database 101 (free docs/learning center)](https://www.pinecone.io/learn/) |
| Open-source vector DB (hands-on) | [ChromaDB Docs](https://docs.trychroma.com/) |

**Checkpoint:** You can build a working RAG pipeline: load docs → chunk → embed → store → retrieve → generate.

---

## Phase 6: AI Agents — Core Concepts (3–4 weeks)

This is where "chatbot" becomes "agent": reasoning, planning, tool use, memory.

| Topic | Resource |
|---|---|
| Full agents course (20 hrs, hands-on, code) | [Hugging Face Agents Course](https://huggingface.co/learn/agents-course) |
| Agentic design patterns (reflection, planning, tool use, multi-agent) | [DeepLearning.AI – Agentic AI (Andrew Ng, ~10 hrs, free to audit)](https://www.deeplearning.ai/courses/agentic-ai/) |
| Code-first agents curriculum (15 lessons, GitHub) | [Microsoft – AI Agents for Beginners](https://github.com/microsoft/ai-agents-for-beginners) |
| ReAct pattern, tool-use, planning basics | [ReAct: Synergizing Reasoning and Acting in LLMs (paper)](https://arxiv.org/abs/2210.03629) |
| Google/Kaggle intensive (5-day, hands-on) | [Kaggle – 5-Day AI Agents Intensive](https://www.kaggle.com/learn-guide/5-day-genai) |

**Checkpoint:** You understand the agent loop (observe → reason → act), tool calling, and memory patterns.

---

## Phase 7: Building Custom Agents — Frameworks (4–5 weeks)

Pick **one** primary framework to go deep on, then skim the others so you can compare.

### 🔹 LangGraph (most popular for controllable, stateful agents)
- [DeepLearning.AI – AI Agents in LangGraph](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/) (taught by LangChain's CEO + Andrew Ng)
- [LangChain Academy – free courses](https://academy.langchain.com/)
- [LangGraph Official Docs](https://langchain-ai.github.io/langgraph/)

### 🔹 CrewAI (role-based multi-agent orchestration)
- [DeepLearning.AI – Multi AI Agent Systems with crewAI](https://www.deeplearning.ai/short-courses/multi-ai-agent-systems-with-crewai/)
- [CrewAI Official Docs](https://docs.crewai.com/)

### 🔹 Claude Agent SDK / Anthropic tooling (build with Claude + MCP)
- [Anthropic Academy](https://www.anthropic.com/learn) — free courses with certificates: Building with the Claude API, Claude Code in Action, Model Context Protocol (MCP)
- [Claude Agent SDK docs](https://docs.claude.com/en/docs/agents-and-tools/claude-agent-sdk/overview)

### 🔹 OpenAI Agents SDK / AutoGen (Microsoft)
- [OpenAI Agents SDK Docs](https://openai.github.io/openai-agents-python/)
- [Microsoft AutoGen Docs](https://microsoft.github.io/autogen/)

### 🔹 Protocols connecting agents to tools/other agents
- [Model Context Protocol (MCP) Docs](https://modelcontextprotocol.io/)
- Agent-to-Agent (A2A) — covered inside Microsoft's AI Agents for Beginners course above

**Checkpoint:** You've built at least one custom agent with tool calling, memory, and a defined goal using a real framework — not just a tutorial copy-paste.

---

## Phase 8: Production, Evaluation & Advanced Topics (ongoing)

| Topic | Resource |
|---|---|
| Evaluating LLM apps/agents | [DeepLearning.AI – Evaluating and Debugging Generative AI](https://www.deeplearning.ai/short-courses/evaluating-debugging-generative-ai/) |
| Efficient inference / serving | [DeepLearning.AI – Fast and Efficient LLM Inference with vLLM](https://www.deeplearning.ai/short-courses/) |
| Agent memory, learning from traces | Latest DeepLearning.AI short courses (check homepage — new ones added monthly) |
| Security for agents | Covered in Microsoft's AI Agents for Beginners (Lesson on Agent Security) |
| Multi-agent system design patterns | [Anthropic – Building Effective Agents (engineering blog)](https://www.anthropic.com/engineering/building-effective-agents) |
| Deployment | [Hugging Face Spaces (free hosting for demos)](https://huggingface.co/spaces) |

---

## 🏗️ Suggested Portfolio Projects (build these as you go)

1. **Basic chatbot** using an LLM API + prompt engineering (Phase 4)
2. **RAG app** — "chat with your own PDFs/notes" (Phase 5)
3. **Single-purpose agent** — e.g., a research agent that searches the web and summarizes (Phase 6)
4. **Multi-agent system** — e.g., a "crew" that plans, writes, and reviews content, or a coding agent with a reviewer agent (Phase 7)
5. **End-to-end deployed project** — wrap one of the above in a simple UI (Streamlit/Gradio) and deploy free on Hugging Face Spaces

---

## 📌 Notes on Free Access

- DeepLearning.AI short-course **videos** are free to watch; some labs/quizzes/certificates now sit behind a paid Pro tier — you can still learn everything from the videos + doing the work yourself in your own environment.
- Anthropic Academy courses are free **with certificates**.
- Hugging Face's LLM and Agents courses are fully free, no paywall.
- Microsoft's GitHub curricula (Generative AI for Beginners, AI Agents for Beginners) are open-source and completely free.

Since this space moves fast, periodically check the DeepLearning.AI and Anthropic Academy homepages for new short courses — several are added every month.

---

*Good luck — build in public, ship small projects at every phase, and don't wait until you "know enough" to start building an agent. That's how you actually learn it.*
