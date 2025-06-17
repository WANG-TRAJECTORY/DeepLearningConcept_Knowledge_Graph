# Knowledge Graph Construction and Visualization

This project leverages LangChain's `LLMGraphTransformer` and large language models (e.g., GPT-4o-mini)  
to automatically generate knowledge graphs from text, and visualize them using NetworkX and Matplotlib with full Chinese font support.

---

## Features

- Reads long text files (e.g., course knowledge base) and splits them into chunks.
- Asynchronously converts text chunks into graph documents containing nodes and relationships via LLM.
- Merges results, prints detailed info and statistical summaries of nodes and relationships.
- Visualizes the knowledge graph with labeled nodes and edges, supporting Chinese characters without encoding issues.
- Provides concise print samples for quick inspection and debugging.

---

## Requirements

Make sure to install the following Python packages:

```bash
pip install langchain langchain-openai matplotlib networkx
```
**Note: Replace the OpenAI API key with your own, and verify the model name is correct.**
