# Aman Atar

<div align="center">

[![Kaggle Expert](https://img.shields.io/badge/Kaggle_Notebooks_Expert-%2330_Worldwide_(Top_0.05%25)-20BEFF?logo=kaggle&logoColor=white)](https://www.kaggle.com/amanatar)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aman_Atar-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aman-atar)
[![MScFE](https://img.shields.io/badge/MSc_Financial_Engineering-WorldQuant_University-0B1D3A?logo=academia&logoColor=white)](https://www.wqu.edu)
[![IIT Hyderabad](https://img.shields.io/badge/AI_%26_ML_Coursework-IIT_Hyderabad-D9381E?logo=google-scholar&logoColor=white)](https://www.iith.ac.in)

</div>

---

Hey, I'm Aman.

I work on quantitative finance models and production ML systems -- mostly focused on what happens when clean math meets noisy market regimes, jump risk, and strict latency budgets.

Currently doing my MSc in Financial Engineering at WorldQuant University (plus AI/ML coursework with IIT Hyderabad). Outside research, I test ideas on Kaggle as a **Kaggle Notebooks Expert** -- currently ranked **#30 worldwide** out of 58,700+ ranked notebooks practitioners (peak #28, 40 medals: 4 Gold, 5 Silver, 31 Bronze).

---

## Featured Systems & Code (Original Flagship Repositories)

| System | Focus & Implementation Details | Stack |
| :--- | :--- | :--- |
| **[auditable-regime-aware-agentic-forecasting](https://github.com/Amanatar/auditable-regime-aware-agentic-forecasting)**<br>`TRACE-Fin` | **Timestamp-restricted regime-aware return forecasting.** Strict causality enforcement (0 lookahead leakage), market regime shift detection, transaction-cost utility optimization, and calibrated 90% conformal prediction intervals. | `Python`, `PyTorch`, `Time-Series ML`, `Regime Detection` |
| **[neural-bates-dml](https://github.com/Amanatar/neural-bates-dml)**<br>Sobolev Pricing Engine<br>[GitHub ↗](https://github.com/Amanatar/neural-bates-dml) · [Live Workbench ↗](https://huggingface.co/spaces/Amanatar/neural-bates-dml) | **Twin-network Sobolev Differential ML surrogate for 10-D Bates SVJD option pricing.** Trained with Sobolev loss on analytical Carr-Madan FFT prices and Greeks. Benchmarked on real SPY options: **1.58× faster calibration** (6.07 s vs. 9.61 s FFT), **10.3× per-surface speedup** (3.26 ms CPU), **340 bps IV RMSE**, and **40.1% Delta MAE reduction** with zero arbitrage violations. | Python, PyTorch, Sobolev Training, Carr-Madan FFT, Bates SVJD |
| **[FinFaithful-RAG](https://github.com/Amanatar/FinFaithful-RAG)**<br>`Grounded Financial RAG & Benchmark` | **SEC EDGAR 10-K grounded retrieval & verification engine.** Benchmarks 4 retrieval pipelines (Direct LLM, BM25, FAISS, Hybrid RRF + Cross-Encoder) across **120 audited Form 10-K questions** (`AAPL`, `MSFT`, `NVDA`, `JPM`, `GOOGL`). Standalone retrieval progression lifts Recall@5 to **70.0%** (MRR@10: 0.3894) with **86.8% verified citation validity**, **100.0% adversarial trap abstention**, and a production Streamlit Community Cloud workbench under 35 MB. | `Python`, `FAISS`, `Sentence-Transformers`, `Cross-Encoder`, `BM25`, `Streamlit`, `LLM-as-a-Judge` |
| **[IRL_Data_Science_-_GenAi_Internship](https://github.com/Amanatar/IRL_Data_Science_-_GenAi_Internship)**<br>`Production GenAI & MLOps` | **Production GenAI & MLOps suite.** Includes FinWiser (financial assistant with Gemini -> NVIDIA NIM LLaMA-3.1-70B 429 circuit-breaker failover on AWS EC2), enterprise RAG via Amazon Bedrock, and centralized MLflow tracking across 5 classification baselines. | `Python`, `AWS EC2`, `Bedrock RAG`, `MLflow`, `Flask`, `Docker` |
| **[google-ai-agents-intensive](https://github.com/Amanatar/google-ai-agents-intensive)**<br>`The Alpha Seeker` | **The Alpha Seeker autonomous multi-agent trading loop built on Google ADK.** Coordinates sequential, parallel, and feedback-loop agents for macro data ingestion, signal evaluation, and max drawdown (<15%) enforcement. | `Python`, `Google ADK`, `Multi-Agent LLMs`, `Technical Analysis` |
| **[hypertension-risk-assessment](https://github.com/Amanatar/hypertension-risk-assessment)**<br>`Clinical Risk Classifier` | **4-stage clinical cardiovascular risk classifier & Flask inference service.** Maps multi-factor telemetry into clinical risk stages (Normal, Stage 1, Stage 2, Crisis) with calibrated probability confidence and automated medical triage recommendations (`pytest` CI verified). | `Python`, `Flask`, `scikit-learn`, `Telemetry Triage` |

---

## Applied Engineering Repositories

- **[practical-deep-learning-for-coders](https://github.com/Amanatar/practical-deep-learning-for-coders):** Deep learning vision architectures, transfer learning pipelines, and tabular neural networks implemented via Fast.ai and PyTorch (8 notebooks & forward/backward pass verified).
- **[student-mental-health-companion](https://github.com/Amanatar/student-mental-health-companion):** Affective state computing assistant combining VADER sentiment analysis, custom emotional lexicon mapping, and dual-mode Gemini/offline dialogue generation with immediate crisis routing.
- **[machine-learning-project](https://github.com/Amanatar/machine-learning-project):** Catalog of 20 supervised, unsupervised, and deep learning implementations across clinical healthcare, finance, NLP, and signal processing (80.3% test accuracy on clinical cardiovascular telemetry).
- **[Project_euler](https://github.com/Amanatar/Project_euler):** Vectorized and dynamic programming solutions to Project Euler problems (1-26) in pure Python (100% mathematical match verified).

---

## Competitive ML on Kaggle (Kaggle Expert)

- **Official Standing:** Kaggle Notebooks Expert -- **#30 Worldwide** (Peak #28) out of 58,736+ ranked practitioners (Top 0.05%).
- **Medal Count:** 40 Medals (4 Gold, 5 Silver, 31 Bronze) with 2,800+ community upvotes across 800+ published research notebooks.
- **Notable Gold Notebooks:**
  - `ans-verifys` (749+ upvotes, Gold) -- Reasoning verification and answer integrity pipelines for competition LLM outputs.
  - `improved-metric-hack-last-call` (196+ upvotes, Gold) -- Post-processing and threshold optimization under non-standard competition loss metrics.
  - `nvidia-nemotron-sfttrainer-training` (176+ upvotes, Gold) -- Supervised fine-tuning pipeline for Nemotron models using HuggingFace TRL.
  - `biohub-geometric-fusion` (172+ upvotes, Gold) -- Graph and tabular geometric feature fusion architecture.

---

## Technical Focus & Tools

- **Quant & Modeling:** Python, PyTorch, LightGBM, XGBoost, CatBoost, Differential ML, Stochastic Calculus, Carr-Madan FFT
- **GenAI & Infrastructure:** FAISS, Sentence-Transformers, Google ADK, Amazon Bedrock RAG, Gemini API, NVIDIA NIM, MLflow, FastAPI, Flask, Docker, AWS EC2
- **Data & Tools:** NumPy, Pandas, SciPy, OpenCV, PostgreSQL, Linux / Bash, Git

---

## Contact

- **Kaggle:** [kaggle.com/amanatar](https://www.kaggle.com/amanatar)
- **LinkedIn:** [linkedin.com/in/aman-atar](https://www.linkedin.com/in/aman-atar)
- **GitHub:** [github.com/Amanatar](https://www.github.com/Amanatar)
- **Email:** [ataraman9@gmail.com](mailto:ataraman9@gmail.com)
