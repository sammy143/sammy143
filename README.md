# Hi, I'm Samuel Emmanuel 👋

**MSc Artificial Intelligence (Distinction track), Ulster University Belfast** — graduating May 2026.
Building ML systems and digging into how models actually work. Interested in mechanistic interpretability, sparse attention, and AI safety.

📍 Belfast, NI · ✉️ [samuelemmanuel520@gmail.com](mailto:samuelemmanuel520@gmail.com) · 🎓 [Emmanuel-s1@ulster.ac.uk](mailto:Emmanuel-s1@ulster.ac.uk) · 🔗 [LinkedIn](https://www.linkedin.com/in/realsammye/)

---

### 🔬 What I work on

- **Interpretability & AI safety** — explainability methods in practice (LIME, Grad-CAM, occlusion-sensitivity validation), with an ongoing interest in mechanistic interpretability and sparse attention for small, domain-specific language models.
- **Applied ML on real-world data at scale** — cross-device transfer learning and semi-supervised pseudo-labelling under distribution shift, on pipelines spanning millions of samples and hundreds of millions of raw rows.
- **LLMs, retrieval & agentic systems** — LoRA fine-tuning, graph-grounded RAG, reward modelling for structured outputs, BDD/DSL specification, and autonomous agentic pipelines.
- **ML systems & MLOps** — GPU-accelerated pipelines (NVIDIA A100s), Azure ML Studio & Azure AI Studio, GCP (Vertex AI), containerised deployment, and testing/monitoring of live endpoints.

**Currently most interested in:** mechanistic interpretability · sparse attention · LLM architecture · AI safety & alignment · neuro-symbolic AI · retrieval-augmented & agentic systems.

---

### 🛠️ Featured Projects

**[🦅 From Flapping to Soaring: ML-Enabled Behavioural Classification & Energy Expenditure in Griffon Vultures](https://github.com/sammy143/Vultures_Project)**
MSc thesis. Cross-device transfer-learning pipeline propagating professionally labelled adult behaviours onto **12.7M unlabelled juvenile accelerometer bursts** (890M+ raw rows) across **74 vultures** — **97.80% stratified CV accuracy**, 91.7% high-confidence surrogate labels. Three-fold ecological validation + VeDBA/ODBA energetics.
`Python` `XGBoost` `scikit-learn` `Polars` `Parquet`

<img src="https://github.com/sammy143/Vultures_Project/raw/main/Graphics/4-Validation/10_gps_validation.png" width="600" alt="GPS-based ecological validation of flight-behaviour classes" />

📓 [5-notebook pipeline](https://github.com/sammy143/Vultures_Project/blob/main/04_Model_Training_andTransfer_Learning.ipynb) · 🖼️ [35 figures](https://github.com/sammy143/Vultures_Project/tree/main/Graphics) · 📄 [Slides](https://github.com/sammy143/Vultures_Project/blob/main/Final-Project-Presentation.pdf)

**[📈 Topology-Aware Bayesian Active Learning](https://github.com/sammy143/quantihack)** — 🏆 QuantiHack 2026 London
Reconstructs black-box functions (incl. real intraday S&P 500 / Google price curves) by guiding a Gaussian Process with a composite acquisition function grounded in topological persistence, analytic curvature, and epistemic uncertainty. **12th of 42 finalists, from 265+ teams.**
`Python` `scikit-learn` `Gaussian Processes` `topopy` `Morse-Smale`

<img src="https://github.com/sammy143/quantihack/raw/main/images/dashboard.jpeg" width="600" alt="Live active-learning dashboard at QuantiHack 2026" />

📄 [Full writeup & architecture](https://github.com/sammy143/quantihack) *(source release pending)*

**[⚙️ spec-forge: Graph-Grounded BDD Specification Compiler](https://github.com/sammy143/spec-forge-overview)**
Converts free-form requirements into auditable Gherkin specs with a provenance trail back to canonical BDD literature (LightRAG). Deterministic multi-component reward harness (parse × anti-pattern × declarative × alignment); LoRA-tuned Qwen2.5-Coder-7B. Adversarial eval gate passed at ΔR = +0.122.
`Python` `Qwen2.5-Coder` `LoRA / Unsloth` `LightRAG` `TRL (GRPO)`

📄 [Architecture, milestones & results](https://github.com/sammy143/spec-forge-overview) *(source release pending)*

**[🧠 Second Brain Portfolio Optimizer](https://github.com/sammy143/portfolio-optimizer)**
Agentic pipeline: reads client profiles from an Obsidian vault, runs 5,000-path Monte Carlo Sharpe optimisation on live market data, generates a personalised investment memo via LLM, writes it back — autonomously. Graceful fallback chains throughout. Built end-to-end at the Techstars Belfast AI sprint.
`Python` `FastAPI` `OpenRouter` `yfinance` `Monte Carlo`

💻 [Source](https://github.com/sammy143/portfolio-optimizer/tree/main/src) · 🖥️ [Dashboard frontend](https://github.com/sammy143/portfolio-optimizer/tree/main/frontend) · 📄 [Design docs](https://github.com/sammy143/portfolio-optimizer/tree/main/docs)

**[🏗️ MLOps in Action: Scalable Loan Default Prediction](https://github.com/sammy143/mlops-load-default)**
End-to-end MLOps pipeline — data engineering (dirty-data injection → cleaning → SMOTE) on Colab, training & orchestration on Azure ML Studio, containerised MLFlow endpoint, plus a full functional/security/performance/scalability/drift testing suite against the live API.
`Python` `Azure ML` `MLFlow` `Locust` `imbalanced-learn`

📓 [Notebook](https://github.com/sammy143/mlops-load-default/blob/main/Comp774_MLOps_FInal.ipynb) · 📄 [Phase 1 slides](https://github.com/sammy143/mlops-load-default/blob/main/Presentation%2B1-Sam.pdf) · 📄 [Phase 2 slides](https://github.com/sammy143/mlops-load-default/blob/main/774_CW2.pdf)

**[🔍 Explaining the Black Box: LIME & Grad-CAM](https://github.com/sammy143/xai772)**
A hands-on XAI investigation on a 120-class dog-breed classifier — superpixel attribution, gradient heatmaps, and a compound Grad-CAM occlusion-sensitivity test (77.6% confidence collapse confirmed the heatmaps were causally meaningful).
`Python` `PyTorch` `LIME` `pytorch-grad-cam` `SHAP`

📄 [Slides](https://github.com/sammy143/xai772/blob/main/Presentation%2B2.pdf) · 📑 [Experiments](https://github.com/sammy143/xai772/blob/main/Experiments.pdf)

**[🕸️ Streamable Content Ontology + Neuro-Symbolic Recommendation](https://github.com/sammy143/ontologycomp759)**
An OWL 2 ontology (6-level hierarchy, inverse/sub-property axioms, HermiT + Pellet reasoning) for explainable OTT content discovery, with a GraphRAG framework for grounding LLM recommendations to traceable reasoning paths.
`OWL 2` `Protégé` `SPARQL` `HermiT / Pellet` `GraphRAG`

📄 [Slides](https://github.com/sammy143/ontologycomp759/blob/main/COM_759_Presentation.pdf) · 📑 [Report and Ontology](https://github.com/sammy143/ontologycomp759/blob/main/Ontology%2BReport.pdf)

---

### 🧰 Stack

`Python` · `PyTorch` · `TensorFlow` · `Transformers / SBERT` · `Azure MLOps` · `GCP (Vertex AI, Dialogflow)` · `Neo4j` · `FastAPI`

---

### ✍️ Writing / Blogs

- **[Beyond Chatbots: Agentic AI, the Next Battleground in Fintech](https://www.linkedin.com/pulse/beyond-chatbots-agentic-ai-next-battleground-fintech-samuel-emmanuel-a1b4e/)** — why the shift from conversational to agentic AI reshapes financial services.
- **[Move 2: How Bad Pedagogy Ruined Math for a Generation](https://www.linkedin.com/pulse/move-2-how-bad-pedagogy-ruined-math-generation-samuel-emmanuel-4o9ce/)** — on how maths is taught, and where it goes wrong.

---

### 🎤 Conferences & Other Contributions

**[BelTech 2026](https://www.linkedin.com/search/results/all/?keywords=%23beltech2026&origin=HASH_TAG_FROM_FEED)** — attended representing **Ulster University**.

Standout talk: **Dave Farley on Vibe Coding** — that engineering is not "writing code" but solving complex problems and structuring complexity; that natural language is too ambiguous for precise engineering, pushing toward goal-directed reasoning and BDD with domain-specific languages (a thread that runs straight into my spec-forge work); and that the engineers who thrive next won't be the ones hoarding context windows, but the critical thinkers who master meta-cognition, problem decomposition, and systems thinking. Other highlights spanned AI and the software supply chain, practical data quality, browser-based privacy-first AI, and AI-driven full-cycle QA.

**Open-source corrections to _Financial Data Engineering_ (O'Reilly), by Tamer Khraisha, Ph.D** — working through the book's PostgreSQL bank-database project, I surfaced and fixed several issues in the official repo (author-acknowledged): correcting table-creation order so `LoanPayment` follows the `Transactions` table it references; changing the `Employee` table's `id INT PRIMARY KEY` to `SERIAL` for consistency with the insert statements; flagging a `load_type_id` → `loan_type_id` typo; and adjusting seed values that violated the `CHECK (balance >= minimum_balance)` constraint. [Writeup](https://www.linkedin.com/posts/realsammye_sql-postgresql-dataengineering-activity-7408132760629829632-uRRX).
