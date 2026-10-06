# Hi, I'm Samuel Emmanuel 👋

**AI Engineer at Nitec Solutions**: agentic development, harness engineering and R&D, building enterprise AI agents on Microsoft Agent Framework, Azure AI Foundry and Copilot Studio.
**MSc Artificial Intelligence (Distinction), Ulster University Belfast, 2026.**
Researching LLMs and ML systems, and digging into how models actually work. Interested in mechanistic interpretability and AI safety.

📍 Belfast, NI · ✉️ [samuelemmanuel520@gmail.com](mailto:samuelemmanuel520@gmail.com) · 🔗 [LinkedIn](https://www.linkedin.com/in/realsammye/)

---

### 🔬 What I work on

- **Agentic systems & harness engineering:** enterprise agents on Microsoft Agent Framework and Azure AI Foundry, MCP tool integration, and harnesses that let coding agents work reliably across sessions (structured repo knowledge, mechanical checks, verifier and reviewer loops).
- **LLMs & retrieval:** LoRA fine-tuning, graph-grounded RAG, reward modelling for structured outputs, and BDD/DSL specification.
- **Applied ML on real-world data at scale:** cross-device transfer learning and semi-supervised pseudo-labelling under distribution shift, on pipelines spanning millions of samples and hundreds of millions of raw rows.
- **ML systems & MLOps:** GPU-accelerated pipelines (NVIDIA A100s), Azure ML Studio & Azure AI Studio, GCP (Vertex AI), containerised deployment, and testing/monitoring of live endpoints.
- **Explainability in practice:** LIME, Grad-CAM and occlusion-sensitivity validation of model attributions.

**Currently most interested in:** mechanistic interpretability · LLM architecture · AI safety & alignment · neuro-symbolic AI · retrieval-augmented & agentic systems.

---

### 🛠️ Featured Projects

**[🦅 From Flapping to Soaring: ML-Enabled Behavioural Classification & Energy Expenditure in Griffon Vultures](https://github.com/sammy143/Vultures_Project)**
MSc thesis. Cross-device transfer-learning pipeline propagating professionally labelled adult behaviours onto **12.7M unlabelled juvenile accelerometer bursts** (890M+ raw rows) across **74 vultures**: **97.80% stratified CV accuracy**, 91.7% high-confidence surrogate labels. Three-fold ecological validation + VeDBA/ODBA energetics.
`Python` `XGBoost` `scikit-learn` `Polars` `Parquet`

<img src="https://github.com/sammy143/Vultures_Project/raw/main/Graphics/4-Validation/10_gps_validation.png" width="600" alt="GPS-based ecological validation of flight-behaviour classes" />

📓 [5-notebook pipeline](https://github.com/sammy143/Vultures_Project/blob/main/04_Model_Training_andTransfer_Learning.ipynb) · 🖼️ [35 figures](https://github.com/sammy143/Vultures_Project/tree/main/Graphics) · 📄 [Slides](https://github.com/sammy143/Vultures_Project/blob/main/Final-Project-Presentation.pdf)

**[📈 Topology-Aware Bayesian Active Learning](https://github.com/sammy143/quantihack)** · QuantiHack 2026 London
Reconstructs black-box functions (incl. real intraday S&P 500 / Google price curves) by guiding a Gaussian Process with a composite acquisition function grounded in topological persistence, analytic curvature, and epistemic uncertainty. **12th of 42 finalists, from 265+ teams.**
`Python` `scikit-learn` `Gaussian Processes` `topopy` `Morse-Smale`

<img src="https://github.com/sammy143/quantihack/raw/main/images/dashboard.jpeg" width="600" alt="Live active-learning dashboard at QuantiHack 2026" />

📄 [Full writeup & architecture](https://github.com/sammy143/quantihack) *(source release pending)*

**[⏰ Nag: Harness Engineering with Cloud Coding Agents](https://github.com/sammy143/reminders-app)**
A reminders app whose notifications get progressively ruder until you leave the house, built as an experiment in harness engineering. Claude Code cloud sessions built each feature through an implementer, verifier and reviewer loop, steered by a repo designed for agents with no memory: an `AGENTS.md` map, docs as the system of record, mechanically enforced layer boundaries and an append-only progress log. Human in the loop for device checks, product calls and merges. **9 features, 8 PRs, 444 tests**; the verifier broke the code up to 21 ways per feature to prove the tests would catch it.
`TypeScript` `React Native` `Expo` `Zustand` `Jest` `Claude Code`

<img src="https://github.com/sammy143/reminders-app/raw/main/docs/design/screens/active-alarm.png" width="260" alt="Nag's active alarm screen, 6 minutes past the leave-by time" />

📄 [Write-up & lessons](https://github.com/sammy143/reminders-app#readme) · 🧭 [Agent map](https://github.com/sammy143/reminders-app/blob/main/AGENTS.md) · 🧠 [Harness memory](https://github.com/sammy143/reminders-app/tree/main/harness)

**[🧠 Second Brain Portfolio Optimizer](https://github.com/sammy143/portfolio-optimizer)**
Agentic pipeline: reads client profiles from an Obsidian vault, runs 5,000-path Monte Carlo Sharpe optimisation on live market data, generates a personalised investment memo via LLM and writes it back, autonomously. Graceful fallback chains throughout. Built end-to-end at the Techstars Belfast AI sprint.
`Python` `FastAPI` `OpenRouter` `yfinance` `Monte Carlo`

💻 [Source](https://github.com/sammy143/portfolio-optimizer/tree/main/src) · 🖥️ [Dashboard frontend](https://github.com/sammy143/portfolio-optimizer/tree/main/frontend) · 📄 [Design docs](https://github.com/sammy143/portfolio-optimizer/tree/main/docs)

**[🏗️ MLOps in Action: Scalable Loan Default Prediction](https://github.com/sammy143/mlops-load-default)**
End-to-end MLOps pipeline: data engineering (dirty-data injection → cleaning → SMOTE) on Colab, training & orchestration on Azure ML Studio, containerised MLFlow endpoint, plus a full functional/security/performance/scalability/drift testing suite against the live API.
`Python` `Azure ML` `MLFlow` `Locust` `imbalanced-learn`

📓 [Notebook](https://github.com/sammy143/mlops-load-default/blob/main/Comp774_MLOps_FInal.ipynb) · 📄 [Phase 1 slides](https://github.com/sammy143/mlops-load-default/blob/main/Presentation%2B1-Sam.pdf) · 📄 [Phase 2 slides](https://github.com/sammy143/mlops-load-default/blob/main/774_CW2.pdf)

<details>
<summary><b>More projects: explainable AI and ontology engineering</b></summary>

<br>

**[🔍 Explaining the Black Box: LIME & Grad-CAM](https://github.com/sammy143/xai772)**
A hands-on XAI investigation on a 120-class dog-breed classifier: superpixel attribution, gradient heatmaps, and a compound Grad-CAM occlusion-sensitivity test (77.6% confidence collapse confirmed the heatmaps were causally meaningful).
`Python` `PyTorch` `LIME` `pytorch-grad-cam`

📄 [Slides](https://github.com/sammy143/xai772/blob/main/Presentation%2B2.pdf) · 📑 [Experiments](https://github.com/sammy143/xai772/blob/main/Experiments.pdf)

**[🕸️ Streamable Content Ontology + Neuro-Symbolic Recommendation](https://github.com/sammy143/ontologycomp759)**
An OWL 2 ontology (6-level hierarchy, inverse/sub-property axioms, HermiT + Pellet reasoning) for explainable OTT content discovery, with a GraphRAG framework for grounding LLM recommendations to traceable reasoning paths.
`OWL 2` `Protégé` `SPARQL` `HermiT / Pellet` `GraphRAG`

📄 [Slides](https://github.com/sammy143/ontologycomp759/blob/main/COM_759_Presentation.pdf) · 📑 [Report and Ontology](https://github.com/sammy143/ontologycomp759/blob/main/Ontology%2BReport.pdf)

</details>

---

### 🧰 Stack

`Python` · `PyTorch` · `TensorFlow` · `Transformers / SBERT` · `Azure MLOps` · `GCP (Vertex AI, Dialogflow)` · `Neo4j` · `FastAPI`

---

### ✍️ Writing

- **[Three Months as an AI Engineer at Nitec](https://lnkd.in/p/e2KbGr-3)**: AI shifts the engineer's job from writing code to judging it, and judgment still requires fluency; knowledge engineering remains foundational to agentic systems.
- **[Beyond Chatbots: Agentic AI, the Next Battleground in Fintech](https://www.linkedin.com/pulse/beyond-chatbots-agentic-ai-next-battleground-fintech-samuel-emmanuel-a1b4e/)**: why the shift from conversational to agentic AI reshapes financial services.
- **[Move 2: How Bad Pedagogy Ruined Math for a Generation](https://www.linkedin.com/pulse/move-2-how-bad-pedagogy-ruined-math-generation-samuel-emmanuel-4o9ce/)**: on how maths is taught, and where it goes wrong.

---

### 🎤 Events

- **[AICON Belfast 2026](https://lnkd.in/p/eGwWxjiR)**: "From Possible to Proven: Agents at Work". Standouts on emergent-schema knowledge graphs over SEC filings with KV-cache acceleration, real-time speech-to-speech voice agents, and AI diffusion across Northern Ireland. My takeaway: speakers on ethics and alignment should define terms like "thinking" and "agentic", and show working knowledge of how these systems actually work.
- **[BelTech 2026](https://www.linkedin.com/search/results/all/?keywords=%23beltech2026&origin=HASH_TAG_FROM_FEED)**: attended representing Ulster University. Standout: Dave Farley on vibe coding, arguing that natural language is too ambiguous for precise engineering and pushing toward BDD with domain-specific languages, a thread that runs straight into my [spec-forge](https://github.com/sammy143/spec-forge-overview) work.
- **[Causal XAI Workshop, AICC at Ulster University](https://lnkd.in/p/ebwEW7xw)**: causal inference, counterfactuals and world models, which sent me to Judea Pearl's *The Book of Why*.

---

### 🔧 Open Source

**Corrections to _Financial Data Engineering_ (O'Reilly), by Tamer Khraisha, Ph.D.** Working through the book's PostgreSQL bank-database project, I surfaced and fixed several issues in the official repo (author-acknowledged): correcting table-creation order so `LoanPayment` follows the `Transactions` table it references; changing the `Employee` table's `id INT PRIMARY KEY` to `SERIAL` for consistency with the insert statements; flagging a `load_type_id` → `loan_type_id` typo; and adjusting seed values that violated the `CHECK (balance >= minimum_balance)` constraint. [Writeup](https://www.linkedin.com/posts/realsammye_sql-postgresql-dataengineering-activity-7408132760629829632-uRRX).
