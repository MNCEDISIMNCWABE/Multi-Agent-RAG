This tool builds a locally hosted multi-agent RAG system with these key functionalities:

- Research Agent: Searches and retrieves relevant AI/ML, and Data Science research papers from a user-specified topic from the [arXiv](https://arxiv.org/) database.

- Response Synthesizer Agent: Processes the retrieved documents, extracts key insights, and generates coherent summaries or answers to user queries.

- Includes a fallback to web search using the [FireCrawl](https://www.firecrawl.dev/) API to ensure comprehensive coverage.

- Leverages [CrewAI](https://docs.crewai.com/introduction) and a locally hosted LLM ([Ollama](https://ollama.com/download)) to analyze the retrieved papers, extract key findings, URLs, and synthesize a comprehensive summary for the user.

- Uses [Streamlit](https://streamlit.io/) for the UI


#### Get the FireCrawl API Key from [FireCrawl](https://www.firecrawl.dev/)
- Setup your FireCrawl API: ``FIRE_CRAWL_API_KEY = "<YOUR_FIRE_CRAWL_API_KEY>"``

### Install dependencies
- ```pip install crewai crewai-tools chonkie[semantic] markitdown qdrant-client fastembed streamlit ollama```


### Run the application:
- ```streamlit run app.py```
