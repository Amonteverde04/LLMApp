# A Privacy First Local RAG App

A Retrieval-Augmented Generation (RAG) application that prioritizes data privacy, low costs, and customizability by processing data locally, using open-source tooling, and utilizing LangChain.

🦾 - RAG is a AI technique used to fetch relevant bits of data from a library to build detailed and accurate responses without only relying on pre-trained knowledge. This means we can reduce hallucinations, manually reference data for response integrity, and easily leverage data the LLM has not been trained on.

Built with:

<a href="https://www.langchain.com/">
  <img src="https://python.langchain.com/img/brand/wordmark-dark.png" width="250" />
</a>
<br />
"LangChain is a framework for developing applications powered by large language models (LLMs)." It simplifies the various stages of a LLM application's lifecycle. It does this by implementing a standard interface for LLMs, embedding models, vector stores and integrates with hundreds of providers.
<br />
<br />
<a href="https://www.deepseek.com/en">
  <img src="https://cdn.deepseek.com/logo.png?x-image-process=image%2Fresize%2Cw_1920" width="250" />
</a>
<br />
DeepSeek-R1 is an open-source reasoning model trained using reinforcement learning. It is built for tasks that require logical thinking and problem-solving. It has a base model and smaller "distilled" versions for different computing environments. Deployable with Ollama.
<br />
<br />
<a href="https://ollama.com/">
  <img src="https://private-user-images.githubusercontent.com/3325447/254932576-0d0b44e2-8f4a-4e99-9b52-a5c1c741c8f7.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NDg5MTUwNTYsIm5iZiI6MTc0ODkxNDc1NiwicGF0aCI6Ii8zMzI1NDQ3LzI1NDkzMjU3Ni0wZDBiNDRlMi04ZjRhLTRlOTktOWI1Mi1hNWMxYzc0MWM4ZjcucG5nP1gtQW16LUFsZ29yaXRobT1BV1M0LUhNQUMtU0hBMjU2JlgtQW16LUNyZWRlbnRpYWw9QUtJQVZDT0RZTFNBNTNQUUs0WkElMkYyMDI1MDYwMyUyRnVzLWVhc3QtMSUyRnMzJTJGYXdzNF9yZXF1ZXN0JlgtQW16LURhdGU9MjAyNTA2MDNUMDEzOTE2WiZYLUFtei1FeHBpcmVzPTMwMCZYLUFtei1TaWduYXR1cmU9MzRjZDJkZjUwNDg0NTAwZjZjYWI5MmFmNjNkZTc5NjMzMGVhMjdmZDRlMjFiNzE3NTY3YjA3ODg1Yjg3OGI3NSZYLUFtei1TaWduZWRIZWFkZXJzPWhvc3QifQ.S5AMl2oXOO2iNI8kp19BEjO74fsvaQHR-jfxpDv9Sbw" width="100" />
</a>
<br />
Ollama is an open-source CLI tool built to help facilitate the deployment and management of local LLMs and embedding models so we do not need to rely on cloud-based services.
<br />
<br />
<a href="https://www.trychroma.com/">
  <img src="https://www.trychroma.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fchroma.d840f629.png&w=1920&q=75&dpl=dpl_BtE42bWKKi9GWtgCSP3GwzzDskMa" width="100" />
</a>
<br />
ChromaDB is a open-source vector database specifically designed for applications with powered by LLMs. It supports: "Embeddings, vector search, document storage, full-text search, metadata filtering, and multi-modal.". We use it store and retrieve vector embeddings (more specifically document embeddings) which are numerical representations of data such as words, images and/or audio that capture meaning and relationships within that data. This allows for algorithms to perform similarity calculations, clustering, classification, and more.
<br />
<br />
<a href="https://streamlit.io/">
  <img src="https://docs.streamlit.io/logo.svg" width="100" />
</a>
<br />
Streamlit is an open-source Python framework used for delivering dynamic data apps with minimal lines of code. 
