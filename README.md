# Intellexa AI

Intellexa AI is a multi-agent, enterprise-grade LLM assistant that combines RAG, LangGraph, LangChain, and LangSmith.

## Features
- RAG pipeline with FAISS
- LangGraph-driven agent workflow
- LangSmith tracing & evaluation
- FastAPI backend + Streamlit UI

## Run Locally

```bash
pip install -r requirements.txt
python backend/ingest.py
uvicorn backend.api:app --reload
streamlit run ui/streamlit_app.py
```

## Evaluate
```bash
python backend/langsmith_eval.py
pytest tests/
```
