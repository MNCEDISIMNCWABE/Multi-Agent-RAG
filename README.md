This tool builds a locally hosted multi-agent RAG system with thesae key functionalities:

- Searches and retrieves relevant AI/ML, and Data Science research papers from a user-specified topic from the arXiv database.

- Includes a fallback to web search using the Firecrawl API to ensure comprehensive coverage.

- Leverages CrewAI and a locally hosted LLM (Ollama) to analyze the retrieved papers, extract key findings, URLs, and synthesize a comprehensive summary for the user.

- Uses Streamlit for the UI

- Get the FireCrawl API Key from [FireCrawl](https://www.firecrawl.dev/)

### Install dependencies
```pip install crewai crewai-tools chonkie[semantic] markitdown qdrant-client fastembed streamlit ollama```
