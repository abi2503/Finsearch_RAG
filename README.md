# FinSearch_AI

**FinSearch_AI** is a real-time financial document intelligence system that combines Hybrid RAG (BM25 + Dense Embeddings), RoBERTa-based sentiment analysis, and directional price movement prediction.

## 🔍 Features

- Hybrid RAG pipeline (BM25 + Vector Embeddings + MMR reranking)
- Real-time Cassandra-backed financial document retrieval
- Fine-tuned RoBERTa for bullish/bearish sentiment analysis on earnings calls
- Stock direction prediction based on sentiment aggregation
- Optional Streamlit dashboard for visualization

## 📁 Project Structure

FinSearch_AI/
├── data_ingestion/ # Earnings calls + stock price ingestion
├── embeddings/ # Sentence embeddings
├── retrieval/ # Hybrid BM25 + vector RAG
├── sentiment_model/ # RoBERTa training and inference
├── linking_analysis/ # Sentiment → stock movement evaluation
├── cassandra_db/ # Cassandra schema and loaders
├── utils/, notebooks/, streamlit_app/
├── README.md, requirements.txt, .gitignore