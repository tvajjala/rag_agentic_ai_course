# Professional Certificate in RAG and Agentic AI
## Course Notebooks

| Module | Notebook | Topics |
|--------|----------|--------|
| 1 | `module1/01_generative_ai_fundamentals.ipynb` | Prompt Engineering, In-Context Learning, LangChain LCEL, Structured Outputs |
| 2 | `module2/02_rag_applications.ipynb` | RAG Pipeline, LangChain, LlamaIndex, Gradio Chatbot UI |
| 3 | `module3/03_vector_databases.ipynb` | ChromaDB, Embeddings, Semantic Search, Recommendation Systems |
| 4 | `module4/04_advanced_rag_faiss.ipynb` | FAISS, Hybrid Retrieval (BM25+Dense), MultiQuery, Contextual Compression |
| 5 | `module5/05_multimodal_ai.ipynb` | GPT-4o Vision, DALL-E 3, Whisper STT, TTS, Cross-Modal Search |
| 6 | `module6/06_ai_agents.ipynb` | Function Calling, LangChain Agents, DataFrame/SQL Agents, Visualization |
| 7 | `module7/07_langgraph_agents.ipynb` | LangGraph, ReAct Agents, Multi-Agent Supervisor, Agentic RAG |
| 8 | `module8/08_crewai_autogen.ipynb` | CrewAI, AG2/AutoGen, Human-in-the-Loop, Framework Comparison |

## Prerequisites
- Python 3.10+
- OpenAI API Key (set in `.env` file as `OPENAI_API_KEY=sk-...`)

## Setup
```bash
pip install langchain langchain-openai langchain-community langchain-chroma
pip install langgraph chromadb faiss-cpu sentence-transformers
pip install llama-index llama-index-llms-openai llama-index-embeddings-openai
pip install gradio crewai ag2 rank-bm25 openai
pip install pandas matplotlib seaborn python-dotenv
```

## Notes
- All notebooks use real-world scenarios with production-grade patterns
- Swap `your-api-key-here` with your actual key or use a `.env` file
- DALL-E and Whisper cells require valid API keys with billing enabled
