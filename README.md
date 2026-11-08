 Bolivia IMF Report Analysis

## Overview
This project analyses Bolivia's 2025 IMF Article IV Consultation Report (Country Report No. 25/116) using a lightweight large language model, retrieval-augmented generation (RAG), and financial data visualisation.

## Tools and Technologies
- *Language Model:* Qwen3-4B (4-bit quantisation)
- *PDF Processing:* PyMuPDF
- *Embeddings:* all-MiniLM-L6-v2
- *Vector Database:* FAISS
- *Data Analysis:* Pandas, NumPy
- *Visualisation:* Matplotlib
- *Environment:* Google Colab
## Implementation
1. *PDF Processing:* Extracts and cleans text, creates token-aware chunks, and generates section summaries.
2. *Financial Analysis:* Identifies seven financial themes and extracts structured macroeconomic indicators.
3. *RAG Pipeline:* Uses semantic search and FAISS to generate evidence-grounded answers.
4. *Dashboard:* Creates a four-panel visualisation of financial themes, economic trends, extraction accuracy, and banking stability.
5. *Extra Credit:* Compares
