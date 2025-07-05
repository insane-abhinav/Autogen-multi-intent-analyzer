# Multi-Agent Text Classification using LLM and Autogen

This project implements a modular, extensible **multi-agent system** powered by **LLMs** and **Microsoft's Autogen Framework**. The system is capable of classifying natural language sentences into multiple domain-specific categories such as **fitness**, **marital**, **sports**, **travel**, and more — using dedicated **LLM agents** for each domain.

Each agent is responsible for evaluating the relevance of a sentence within its scope and returns a label such as `"interested"`, `"uncertain"`, or `"not_interested"`.

---

## Use Case

- Multi-domain sentence classification
- Fine-grained control using domain-specific agents
- Scalable to any number of domains (fitness, marital, sports, travel, shopping, etc.)
- Extendable and interpretable classification via language-based reasoning
