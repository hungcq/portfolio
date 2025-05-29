---
weight: 5
title: "Knowledge Repo - RAG Chatbot"
hlink: http://knowledge-repo-chatbot.hungcq.xyz
github: https://github.com/hungcq/knowledge-repo-rag
technologies: Node.js, Python, React.js, Qdrant, vLLM, GPT4All, LLaMA, OpenAI
cover:
  image: /images/knowledge-repo-rag.png
summary: >
  I wanted to understand how a Retrieval-Augmented Generation (RAG) application works,
  so I built this chatbot from scratch to answer questions using resources from my knowledge repo.
---

I wanted to understand how a Retrieval-Augmented Generation (RAG) application works,
so I built this chatbot from scratch to answer questions using resources from my knowledge repo.

This is a **Node.js + Python + React.js** project with two versions:
- Local version: uses **Qdrant** as the vector database, **Nomic** for text embeddings (via vLLM),
  and a **LLaMA**-based model running locally with **GPT4All**.
- API-based version: uses **OpenAI embeddings** and queries **GPT via OpenAI API**.

Things I'd like to improve (when time permits):
- Add a GitHub pipeline to automatically update the vector store whenever I update the knowledge repo.
- Deploy the local version to the cloud (though that might cost me a bit 😂).