# Built-an-AI-Powered-X-Twitter-Post-Generator-with-LangGraph-
# 🤖 AI-Powered X (Twitter) Post Generator with LangGraph

An automated workflow built with **LangGraph** and **OpenAI** that generates, evaluates, and optimizes X (Twitter) posts until they’re viral-worthy 🚀  

This project shows how to combine multiple LLM agents into a loop where:
- One model **writes tweets**
- Another model **evaluates them ruthlessly**
- A third model **optimizes them based on feedback**
- State keeps track of **tweet history & feedback**

---

## ✨ Features
- 🔹 **Funny Tweet Generator** – creates original, hilarious, meme-style posts  
- 🔹 **Tweet Evaluator** – checks humor, originality, virality, format & punchiness  
- 🔹 **Tweet Optimizer** – improves weak tweets using structured feedback  
- 🔹 **Iteration Control** – automatically stops when tweet is approved or max loops reached  
- 🔹 **State Memory** – keeps a record of all generated tweets and feedback history  

---

## 🛠️ Tech Stack
- [LangGraph](https://github.com/langchain-ai/langgraph) – state machine for LLMs  
- [LangChain](https://github.com/langchain-ai/langchain) – LLM orchestration  
- [OpenAI GPT Models](https://platform.openai.com) – tweet generation & evaluation  
- [Pydantic](https://docs.pydantic.dev/) – structured output validation  
- Python 3.10+  

---

## ⚙️ Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/zafarullah4050/Experimenting-with-LangGraph-Gemini-API-for-AI-Powered-Sentiment-Feedback-Analysis.git
   cd Experimenting-with-LangGraph-Gemini-API-for-AI-Powered-Sentiment-Feedback-Analysis
