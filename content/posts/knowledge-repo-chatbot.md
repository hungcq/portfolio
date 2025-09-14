---
weight: 2
title: "Knowledge Repo - RAG Chatbot"
hlink: https://knowledge-repo-chatbot.hungcq.com
github: https://github.com/hungcq/knowledge-repo-rag
technologies: Node.js, Socket.IO, React.js, Qdrant, PostgreSQL, OpenAI, vLLM, GPT4All, LLaMA
cover:
  image: /images/knowledge-repo-rag.png
summary: >
  I wanted to understand how a Retrieval-Augmented Generation (RAG) application works,
  so I built this chatbot from scratch to answer questions using resources from my knowledge repo.
---

I built Knowledge Repo RAG Chatbot to learn how Retrieval-Augmented Generation (RAG) applications work end-to-end.
It’s a chatbot that answers questions using resources from [my own knowledge repository](https://knowledge-repo.hungcq.com).

This is a Node & React project has two flavors:
- Local stack: **Qdrant** (vector DB), **Nomic embeddings** (via vLLM), and a **LLaMA** model with GPT4All.
- Cloud stack: **OpenAI embeddings**, **Qdrant Cloud**, and GPT completions via **OpenAI API**.

Key features include:
- Data ingestion pipeline
- Real-time chat with token streaming
- Chat memory, history, and automatic title generation
- Automated build and deployment

Planned improvements:
- Pipeline to auto-update the vector store when the repo changes
- Account system, authentication, rate-limit
