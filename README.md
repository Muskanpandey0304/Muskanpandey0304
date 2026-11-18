# Hi, I'm Muskan Pandey 👋

I build end-to-end AI and data projects: LLM inference engines, RAG systems, agent safety tooling, and SQL analytics.
Based in Palghar, India. **Open to Junior AI Engineer, LLM Engineer, Data Scientist and Data Analyst roles.**

[LinkedIn](https://linkedin.com/in/muskan-pandey-84a90733b) · [Email](mailto:mpandey9385@gmail.com)

---

## 🚀 Featured Projects

### 🧠 [TuringServe](https://github.com/Muskanpandey0304/TuringServe): LLM inference server built from scratch
OpenAI-compatible server for NVIDIA Turing GPUs (T4, GTX 16xx, RTX 20xx) with paged KV cache, continuous batching, CUDA graphs and custom Triton tensor-core kernels.
In my benchmarks on a single T4 (Qwen2.5-1.5B), cold prefill of an 8k-token prompt took **1.68 s vs 11.07 s for vLLM**, and throughput at 64 clients was **1,805 vs 1,308 tok/s**. A 2-hour soak test ran 40k requests with zero errors.
`Python · PyTorch · Triton · FastAPI`

### 🛡️ [GuardML](https://github.com/Muskanpandey0304/GuardML): safety layer for LLM agents
An MLOps diagnostic agent whose tool calls pass through "ToolGuard", a policy layer with deny-by-default rules, risk scoring, argument provenance and human approval.
On my GuardBench benchmark, attack success dropped from **100% (44/44) with no guard to 5% (2/44)**, with benign tasks still completing. 659 tests and CI.
`Python · FastAPI · MLflow · DVC · Docker`

### 🔎 [AdaptiveRAG](https://github.com/Muskanpandey0304/AdaptiveRAG): RAG from scratch, no frameworks
Question answering over 26 arXiv papers with a query router, hybrid BM25 + vector retrieval, reranking, citations, and refusal when evidence is weak. Evaluated on held-out questions (hit@5 **0.93**) and on the SciFact benchmark. Runs locally with Ollama.
`Python · FAISS · Sentence-Transformers · Streamlit`

### 📊 [Olist Revenue Leak Analysis](https://github.com/Muskanpandey0304/Olist_Revenue_Leak_Analysis): end-to-end data analysis
Analysis of ~100k e-commerce orders (R$13.2M revenue). SQL star schema with 20 automated data tests. Finding: only **3% of customers buy twice**, and late delivery is not the cause. Also includes a late-delivery risk model (ROC AUC 0.72), a regional growth analysis using IBGE data, and Excel and Power BI reporting.
`Python · SQL · Excel · Power BI`

### More
- [Hand Sign Language](https://github.com/Muskanpandey0304/Hand_Sign_language): real-time ASL hand-sign recognition from a webcam (MediaPipe + neural network).
- [Phishing URL Detection](https://github.com/Muskanpandey0304/Main_phishing_url_detection): Flask app that extracts 30 URL features and classifies links with a Keras model.
- [Data Scraping Forge](https://github.com/Muskanpandey0304/Data_scraping_forge): async scraping toolkit with HTML to PDF/Markdown conversion and GitHub code harvesting.

## 🛠️ Skills

**Languages:** Python, SQL
**LLM / AI:** LLM inference, RAG, agents, evaluation, PyTorch, Triton, TensorFlow/Keras
**Data:** pandas, star-schema modelling, statistics, Excel, Power BI
**Tools:** FastAPI, Docker, MLflow, DVC, Streamlit, pytest, GitHub Actions, Git

## 📫 Let's connect

Looking for a Junior AI Engineer, LLM Engineer, Data Scientist or Data Analyst role. Reach me on [LinkedIn](https://linkedin.com/in/muskan-pandey-84a90733b) or at mpandey9385@gmail.com.
