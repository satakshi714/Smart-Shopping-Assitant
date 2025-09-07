# Smart-Shopping-Assitant
🛒 Smart Shopping Assistant – Multi-Agent AI Project
📌 Problem Statement

When shopping online, users are often overwhelmed by too many options. Choosing the best product requires manual research, comparison, and evaluation of alternatives. This process is time-consuming and inefficient.

The Smart Shopping Assistant solves this problem by using multiple AI agents that collaborate to:

Understand the user’s query.

Research relevant products.

Compare them on key features.

Recommend the best option.

🤖 Why Multi-Agent AI?

AI agents are suitable because product selection is a multi-step task. Each step can be delegated to an agent:

The User Query Agent processes what the user is asking for.

The Research Agent fetches candidate products.

The Comparison Agent evaluates trade-offs between products.

The Recommendation Agent gives a clear best option.

This modular design enables independent operation while allowing agents to collaborate for a complete solution.

📝 Project Description

The Smart Shopping Assistant is implemented entirely in a Jupyter Notebook. It uses LLMs through Hugging Face to simulate product research, comparison, and recommendation.

🔗 Agent Interactions

User Query Agent → Passes the raw query (e.g., “budget smartphone under 300 dollars”).

Research Agent → Suggests 3 relevant products.

Comparison Agent → Compares the suggested products.

Recommendation Agent → Recommends the single best product.

Agents pass outputs sequentially, forming a collaborative pipeline.

🛠️ Tools, Libraries, and Frameworks Used

Python

Hugging Face Hub (InferenceClient) – for connecting to hosted LLMs

Transformers – NLP utilities

ipywidgets – for interactive input (if needed)

pandas, numpy – data handling

IPython.display – notebook display support

🧠 LLM Selection

Chosen Model: mistralai/Mistral-7B-Instruct-v0.2 (via Hugging Face Inference API).

Ideal Models: GPT-4 or Claude 3 – for more advanced reasoning and nuanced recommendations.

Free/Open Options:

Hugging Face models (e.g., OPT, Mistral).

GPT-3.5 (via OpenAI).

👉 Justification: Mistral-7B was selected since it’s open-source, free-tier accessible via Hugging Face, and capable of handling basic product recommendation tasks.
