# Timothy Balch

**Data Scientist | Marketing Analytics, Machine Learning & AI Engineering**

Thirteen years building decision systems across subscription media, public health, and energy. Subscriber lifecycle and growth, marketing measurement and causal inference, multi-agent LLM systems, and forecasting under uncertainty. I ship the pipeline, the model, and the service that serves it.

[timbalchtb@gmail.com](mailto:timbalchtb@gmail.com) · [LinkedIn](https://www.linkedin.com/in/timothybalch/)

---

## Selected Work

### [Product-Trend-AI](https://github.com/CodeBalch25/Product-Trend-AI)
Hierarchical multi-agent system for product trend discovery and multi-platform listing management. A Qwen-2.5 72B coordinator delegates to specialist agents on Llama-3.3 70B, DeepSeek R1, and Llama-3.2 11B, each with a defined role and evaluation remit. Autonomous self-healing with human approval gates before anything publishes.

Five-service Docker Compose topology, FastAPI and Uvicorn, Celery across 32 workers, Redis for queue and cache, PostgreSQL 15 behind SQLAlchemy 2.0 with Alembic migrations, React dashboard. Amazon SP-API via boto3, Selenium and BeautifulSoup collection, pytrends signals, JWT and bcrypt auth, Pydantic v2 throughout.

`Python` `FastAPI` `Celery` `Redis` `PostgreSQL` `SQLAlchemy` `Alembic` `Docker Compose` `React` `Anthropic` `OpenAI` `Groq`

### [nomadvpn-pro](https://github.com/CodeBalch25/nomadvpn-pro)
Live commercial product. VPN router provisioning service for remote workers, running end to end from marketing site through checkout to fulfillment.

Next.js 14 and React 18 on TypeScript 5.9, Prisma 5 over PostgreSQL 16, Stripe payments, Resend transactional email, Radix UI and Tailwind with framer-motion. Multi-stage Docker build on node:20-alpine with separate deps, builder, and runner layers for Railway deployment. Compose-managed Postgres with health checks, Zod validation, Vercel analytics and speed insights.

`TypeScript` `Next.js` `React` `Prisma` `PostgreSQL` `Stripe` `Docker` `Tailwind` `Zod`

### [dealflow](https://github.com/CodeBalch25/dealflow)
Real estate investment analyzer exposed as a **Model Context Protocol server**, so an AI assistant can call the underlying analysis engine directly. Three typed tools with JSON Schema contracts: `analyze_property`, `get_market_data`, and `compare_properties`.

Express 5 API, JWT and bcrypt auth, PostgreSQL and SQLite, Groq and Hugging Face inference for valuation commentary and market sentiment.

`Node.js` `MCP` `Express` `PostgreSQL` `SQLite` `Groq` `Hugging Face` `JWT`

### [financial-app](https://github.com/CodeBalch25/financial-app)
Full-stack budgeting, net worth, and investment opportunity tracker with LLM-generated insight summaries and scheduled recalculation.

React 18 with React Router and Recharts, Express API, SQLite, Groq SDK, node-cron scheduling, JWT and bcrypt auth.

`React` `Express` `SQLite` `Groq` `node-cron` `Recharts`

### [Download-Publications-fro-Pubmed-](https://github.com/CodeBalch25/Download-Publications-fro-Pubmed-)
Automated literature acquisition across PubMed and PubMed Central. Bulk search, PDF retrieval, and metadata extraction with resume capability for long-running jobs and rotating user agents.

`Python` `pymed` `BeautifulSoup` `lxml` `pdfminer`

### [Netflix_movie_recommendation](https://github.com/CodeBalch25/Netflix_movie_recommendation)
Content-based and collaborative recommender over 8,000+ titles. TF-IDF vectorization with cosine similarity ranking.

`Python` `scikit-learn` `NLP` `pandas`

### [Face_Mask_Detection_Python](https://github.com/CodeBalch25/Face_Mask_Detection_Python)
Real-time detection on MobileNetV2 with transfer learning, running against both image and video streams behind a Streamlit interface.

`TensorFlow` `Keras` `OpenCV` `Streamlit` `imutils`

### [Loan-predictions-using-keras](https://github.com/CodeBalch25/Loan-predictions-using-keras)
Binary classification network for credit risk over applicant financial and demographic features, with the trained model serialized for reuse.

`Keras` `TensorFlow` `scikit-learn`

### [Machine-Learning-Tensorflow.js](https://github.com/CodeBalch25/Machine-Learning-Tensorflow.js)
Browser-native ML with live training visualization. Linear regression on King County housing and binary classification, training in the client with no backend.

`TensorFlow.js` `JavaScript`

---

## Capabilities

<details>
<summary><b>Subscriber Growth &amp; Lifecycle</b></summary>

Acquisition, retention, churn and cancel modeling, lifetime value, early-tenure success scoring, cohort and survival analysis, win-back and save-desk targeting, subscriber base decomposition into rate and mix effects.

The deepest applied specialty. Gross add, disconnect, and net add mechanics at account and subscription grain.

</details>

<details>
<summary><b>Experimentation &amp; Causal Inference</b></summary>

A/B and multi-armed design, power and minimum detectable effect before launch, pre-registered decision rules, CUPED and CUPAC variance reduction, sequential and always-valid inference with mSPRT and confidence sequences, correct randomization unit including cluster, switchback, and geo holdout.

Staggered-adoption difference-in-differences via Callaway-Sant'Anna, Sun-Abraham, and Borusyak imputation, Goodman-Bacon decomposition, synthetic control and synthetic DiD with placebo-in-space and placebo-in-time, heterogeneous treatment effects through DR, R, and X-learners, causal forests, double machine learning evaluated on Qini and policy value, regression discontinuity with bias-corrected robust intervals, instrumental variables with first-stage diagnostics and explicit LATE interpretation.

`statsmodels` `pyfixest` `linearmodels` `EconML` `CausalML` `DoWhy` `PyMC` `NumPyro`

</details>

<details>
<summary><b>Statistical Inference</b></summary>

Hierarchical Bayesian partial pooling with non-centered parameterization on sparse cells, cluster-robust standard errors at the randomization unit, wild cluster bootstrap when clusters are few, ratio-metric inference via delta method, Fieller, and jackknife, Benjamini-Hochberg FDR against family-wise control, DAG-based bias diagnosis covering collider stratification, immortal time, and survivorship, simulation-first estimator validation, Monte Carlo methods.

</details>

<details>
<summary><b>Machine Learning</b></summary>

Supervised and unsupervised learning, gradient boosting, random forests, explainable boosting machines and SHAP attribution, KMeans and density-based clustering, ensembles and stacking, deep learning and transfer learning, NLP, computer vision, recommender systems, survival models, calibration and model evaluation, hyperparameter optimization, drift monitoring, retraining triggers, and MLOps.

Interpretable models where the reason matters as much as the ranking.

`scikit-learn` `LightGBM` `XGBoost` `CatBoost` `AutoGluon` `TensorFlow` `Keras` `InterpretML` `Optuna` `MLflow` `lifelines` `scikit-survival`

</details>

<details>
<summary><b>AI &amp; LLM Engineering</b></summary>

Multi-agent orchestration and hierarchical delegation, agent role design and evaluation, tool-using agents with typed contracts, Model Context Protocol server authoring, RAG and vector search, prompt and context engineering, structured output and schema enforcement, self-healing and approval-gated autonomy, tracing and evaluation, headless orchestration, model routing across providers.

`Anthropic` `OpenAI` `Groq` `Azure OpenAI` `Qwen` `Llama` `DeepSeek` `MCP` `LangGraph` `LangSmith` `DSPy` `Hugging Face` `vLLM` `ChromaDB` `Databricks Vector Search`

</details>

<details>
<summary><b>Marketing Analytics</b></summary>

Customer segmentation, response propensity and uplift modeling, campaign optimization and audience construction, attribution, behavioral analytics, pricing and price elasticity, market basket and product affinity, geo incrementality, KPI and metric definition.

</details>

<details>
<summary><b>Forecasting &amp; Time Series</b></summary>

Demand and volume forecasting, hierarchical and reconciled forecasts, probabilistic and quantile forecasting with P10/P50/P90 rather than point estimates, decline curve analysis, intermittent demand, anomaly detection, seasonality and utilization modeling, backtesting and rolling-origin evaluation.

`Prophet` `ARIMA` `statsforecast` `Nixtla` `Chronos-2` `hierarchicalforecast`

</details>

<details>
<summary><b>Data Engineering &amp; Platforms</b></summary>

Distributed pipelines, ETL and ELT, orchestration and scheduling, distributed task queues, streaming and change data capture, data quality and contract enforcement, semantic and dimensional modeling, point-in-time correctness and leakage control, partitioning and performance tuning, lineage.

`Azure Databricks` `Spark` `Delta Lake` `Unity Catalog` `MLflow` `Snowflake` `Snowpark` `Apache Iceberg` `Airflow` `Celery` `dbt` `Great Expectations` `OpenLineage` `PySpark` `Polars` `DuckDB`

</details>

<details>
<summary><b>Software, Backend &amp; Infrastructure</b></summary>

Python, SQL, JavaScript, TypeScript. REST API design, FastAPI and Express services, async workers and job queues, relational schema design and migrations, ORMs, authentication with JWT and bcrypt, payment integration, transactional email, caching, containerization and multi-stage builds, service orchestration, health checks, CI/CD.

`FastAPI` `Express` `Next.js` `React` `Docker` `Docker Compose` `PostgreSQL` `Redis` `Prisma` `SQLAlchemy` `Alembic` `Stripe` `Node.js`

</details>

<details>
<summary><b>Business Intelligence</b></summary>

Executive reporting, dashboard and semantic layer design, metric governance and certified definitions, self-serve enablement so the analyst stops being the bottleneck.

`Power BI` `DAX` `TMDL` `Tabular Editor` `Tableau` `Looker`

</details>

<details>
<summary><b>Economics &amp; Econometrics</b></summary>

Panel methods, fixed and random effects, price elasticity and demand estimation, netback and basis differential modeling, constrained-network and locational marginal pricing, capacity economics, unit economics and contribution margin.

</details>

<details>
<summary><b>Engineering Foundations</b></summary>

Linear algebra, calculus and real analysis, probability and statistics, optimization, numerical methods, discrete mathematics, algorithms and data structures, distributed systems.

Petroleum engineering degree still in active use: reservoir and transport modeling, differential equations, thermodynamics, fluid mechanics, nodal analysis to find the binding constraint, material balance as a conservation check, pressure transient analysis for diagnosing from the derivative rather than the level.

</details>
