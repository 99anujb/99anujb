# Hi, I'm Anuj Bansal 👋

**MS Data Science @ UMass Dartmouth** (GPA: 3.6 · Graduating May 2026)
**B.Tech Mechanical Engineering** · Punjab Technical University
📍 Dartmouth, Massachusetts · 📧 99anujbansal@gmail.com · 📞 (508) 965-2806
🌐 **[portfolio-mu-inky-15.vercel.app](https://portfolio-mu-inky-15.vercel.app)**

---

## About Me

Data practitioner with 4+ years of growth and analytics experience in EdTech, now finishing an MS in Data Science at UMass Dartmouth. Graduate research in deep learning for scientific imaging (3rd Place, ASEE NE 2026). My portfolio spans predictive modeling, customer analytics, deep learning research, interactive dashboards, and — most recently — production LLM agents (Claude-driven pipelines for content, resumes, and outreach automation).

**Highlights:**
- 3rd Place, Graduate Poster — ASEE NE Section Conference 2026 (deep learning research on AFM surface reconstruction)
- Led a two-stage Attention U-Net pipeline achieving **97.1% median height recovery** and **0.77 nm MAE** on nanoscale surface prediction
- Quantified **$4.1M in revenue at risk** via CLV modeling and customer segmentation
- Projected **$1.2M in incremental revenue** via KPI funnel analysis; identified **$2M in M&A synergies** through valuation work
- Shipped 3 production Claude-powered agents (daily LinkedIn content pipeline, resume tailoring, cold-outreach automation) running on GitHub Actions cron with email approval gates

I'm actively seeking **Data Scientist, Data Analyst, or Business Analyst** roles starting May 2026.

---

## What I'm Building

| Project | Description | Stack | Status |
|---------|-------------|-------|--------|
| 🤖 [LinkedIn Auto-Post Agent](https://github.com/99anujb/linkedin-agent) | Autonomous daily LinkedIn content pipeline — Claude generates drafts from RSS + voice profile, Gemini/Unsplash image generation, SQLite tracker, GitHub Actions cron, Buffer API scheduling with Gmail approval gate | Python, Claude API, Buffer API, Gemini, GitHub Actions, SQLite | ✅ Live |
| 📝 [Resume & Referral Builder](https://github.com/99anujb/resume-and-referral-builder) | Terminal-driven ATS-aware resume tailoring + cold-outreach pipeline — Claude reads master profile + JD to produce tailored resume PDF, cover letter, and 3-role outreach bundle; SQLite tracker, Apify discovery, Apollo enrichment | Python, Claude API, Apify, Apollo, SQLite | ✅ Live |
| 📄 [Resume Refiner](https://github.com/99anujb/resume-refiner) | Tailor 1-page ATS-aware resumes + cover letters to any JD via Claude Code terminal workflow — JD scoring across 6 weighted dimensions, red-flag detection, WeasyPrint PDF rendering, no paid API required | Python, Claude Code, WeasyPrint, SQLite | ✅ Live |
| 🔬 [AFM Height Map Reconstruction](https://github.com/99anujb/AFM-Height-Reconstruction-DL) | Two-stage deep learning pipeline reconstructing nanoscale AFM surface height maps using a Size-Conditioned Attention U-Net — 97.1% median height recovery, 0.77 nm MAE, 3rd Place ASEE NE 2026 | PyTorch, ResNet18, Attention U-Net, Custom Loss | ✅ Complete |
| 📉 [ChurnShield AI](https://github.com/99anujb/customer-churn-prediction) | End-to-end churn system: Optuna-tuned XGBoost (0.8493 ROC-AUC, 76% recall), K-Means segmentation, CLV modeling ($4.1M at risk), Kaplan-Meier survival analysis — live Streamlit dashboard | XGBoost, Optuna, SHAP, K-Means, Lifelines, Streamlit | ✅ Complete |
| 🏥 [Healthcare Disease Risk Prediction](https://github.com/99anujb/Healthcare-Disease-Risk-Prediction) | Multi-disease patient risk scoring system (Heart Disease, Diabetes, Chronic Kidney Disease) with SHAP explainability, calibrated risk scores, fairness audits, and an interactive what-if simulator for clinical decision support | Scikit-learn, SHAP, Fairlearn, Streamlit | ✅ Complete |
| 📈 [Stock Price Prediction Dashboard](https://github.com/99anujb/stocksense) | Real-time ML dashboard fetching live market data via Alpaca API, engineering 14 technical indicators, predicting next-day prices for 5 major stocks (~1-2% MAE) with SHAP per-prediction explainability | Random Forest, SHAP, Alpaca API, Streamlit | ✅ Complete |
| 📊 [S&P 500 Sector Intelligence](https://github.com/99anujb/sp500-sector-intelligence) | Interactive Tableau dashboard analyzing S&P 500 sector performance 2013–2018 across 619K records and 11 sectors — live at bit.ly/sp500-tableau | Tableau, Python, Pandas | ✅ Live |
| 🌍 [Sustainable Fashion Trends Dashboard](https://github.com/99anujb/sustainable-fashion-viz) | Interactive D3.js data visualization dashboard exploring 5,000 fashion brand records across 10 countries (2010–2024) — choropleth maps, bubble overlays, animated year playback, and country-level drill-down charts | D3.js, TopoJSON, Vanilla JS, HTML/CSS | ✅ Complete |
| 🎵 [Hybrid Music Recommendation System](https://github.com/99anujb/HybridMusicRecommender) *(group project)* | Hybrid recommender on 93,185 Spotify tracks combining content-based KNN filtering with XGBoost popularity prediction (R² 0.474, 74% accuracy) via weighted hybrid scoring | XGBoost, Random Forest, KNN, scikit-learn | ✅ Complete |
| 🍽️ [Zomato Restaurant Rating Prediction](https://github.com/99anujb/zomato-rating-predictor) | End-to-end ML pipeline on 71,730 records predicting restaurant ratings using Extra Trees Regressor — includes full EDA, Flask web app for live predictions, and complete system design documentation | Extra Trees, Random Forest, Flask, scikit-learn | ✅ Complete |
| 🗃️ [Interactive Document Visualization Tool](https://github.com/99anujb/declassified-docs-explorer) | Python ETL pipeline extracting 111 summaries from 5 U.S. intelligence agency text files (CIA, FBI, NSA, DIA, USCBP), powering an interactive D3.js frontend with real-time search and drag-and-drop workspace | Python, Pandas, D3.js, Sortable.js | ✅ Complete |
| 🎨 [3D Portfolio Website](https://github.com/99anujb/Portfolio) | Interactive 3D portfolio showcasing Data Science & ML projects — React + Three.js scenes, GSAP animations, Rapier physics, deployed on Vercel | React, Three.js, GSAP, Rapier, Vercel | ✅ Live |
| 🔍 Fraud Detection Dashboard | Financial anomaly detection comparing classical vs neural approaches | Isolation Forest, Autoencoder, Plotly | 🔜 Coming Soon |

---

## Research Highlight — AFM Height Map Reconstruction

> **Deep Learning–Based Reconstruction of AFM Height Maps from TIFF Images Using a Size-Conditioned Attention U-Net**
> UMass Dartmouth · Department of Data Science · Advisor: Dr. Vijaya Chalivendra
> **3rd Place — ASEE NE Section Conference, 2026**

A two-stage deep learning pipeline for automated surface topography prediction:

- **Stage 1 — SizeRegressor** (ResNet18, ~11M params): Predicts AFM scan dimensions from TIFF images · **75.8% accuracy · 3.03 µm MAE**
- **Stage 2 — Size-Conditioned Attention U-Net** (~15.7M params, FiLM conditioning at every decoder level): Reconstructs Z-height maps conditioned on predicted scan size · **97.1% median height recovery · 0.77 nm MAE** — a 75-point improvement over baseline
- Dataset: 89 original AFM scans augmented to 504 training pairs across 7 scan sizes (1–80 µm²) with group-based anti-leakage splits
- Custom **AFMLoss v2** function: 0.5 × L1 + 0.3 × Std + 0.2 × Range (Std and Range terms prevent blurry mean predictions and enforce correct dynamic range)
- Outputs: Gwyddion-compatible XYZ point cloud files + Ra/Rq/Rz surface roughness metrics

---

## Professional Background

Before my MS, I spent 4+ years in data-driven growth and analytics roles at EdTech and manufacturing companies in India:

- **Scaler Academy** *(Senior Growth Analyst)* — Built Python predictive models (22% lead scoring lift, 15% conversion boost); K-Means segmentation on 12,000+ prospects (18% email response lift); automated KPI dashboards in Tableau/Power BI; funnel analysis projecting $1.2M in incremental revenue
- **Unacademy** *(Growth Analyst)* — CLV and churn models forecasting 6-month revenue for a $5M portfolio; A/B testing across 3,000 contacts (+9% conversion); audience segmentation driving 14% campaign ROI lift
- **Vedantu** *(Business Analyst)* — M&A due diligence identifying $2M in synergies; SQL-driven reporting improving accuracy by 30% and cutting turnaround from 48h to 12h; Tableau dashboards accelerating decision cycles by 20%
- **GATES India** *(Production Enhancement Assistant)* — Time series analysis for labor allocation; statistical bottleneck analysis in manufacturing operations

---

## Technical Skills

**Languages & Querying**
Python · SQL · JavaScript · R

**ML & Deep Learning**
Scikit-learn · XGBoost · PyTorch · CNNs · Attention U-Net · ResNet · Transfer Learning · Custom Loss Functions · Hyperparameter Tuning (Optuna) · Survival Analysis (Kaplan-Meier, Cox PH)

**LLM & Agent Engineering**
Claude API · Claude Code workflows · Prompt Engineering · Agentic Pipelines · RAG · Voice / Style Profiling · Gemini API · Buffer API · RSS Ingestion · GitHub Actions cron · Email-Gated Approval Loops

**Data & EDA**
Pandas · NumPy · Feature Engineering · Data Cleaning · Statistical Modeling · ETL Pipelines · Data Mining

**Explainability & Analytics**
SHAP (TreeExplainer, KernelExplainer) · Fairlearn · A/B Testing · Funnel & Cohort Analysis · KPI Tracking · Churn Modeling · CLV · Revenue Forecasting · Financial Modeling

**Visualization & BI**
Tableau · Power BI · Matplotlib · Seaborn · Plotly · D3.js · TopoJSON · Three.js · GSAP

**Scientific Computing**
OpenCV · AFM Image Processing · Z-Height Map Analysis · Image Normalization · Numerical Computing

**Tools & Deployment**
Jupyter · Git · GitHub · GitHub Actions · VS Code · Flask · FastAPI · Streamlit · Docker · AWS (S3, EC2) · Vercel · GitHub Pages · WeasyPrint · SQLite

---

## Education

🎓 **MS Data Science** — University of Massachusetts Dartmouth (May 2026)
GPA: 3.6 · Coursework: Machine Learning, Deep Learning, Data Mining, Statistical Methods, Database Management, Data Visualization, Cloud Computing (AWS)

🎓 **B.Tech Mechanical Engineering** — Punjab Technical University (June 2020)
Focus: Engineering Mathematics, Statistics, Operations Research, Manufacturing Systems

---

## Leadership

**Treasurer & Executive Board Member** — Indian Student Association, UMass Dartmouth
Managed $20,000+ in budgets · Organized cultural festivals with 300+ attendees · Led sponsorship and fundraising efforts

**Student Ambassador** — International Student & Scholar Center, UMass Dartmouth
Mentored incoming international students on academics and campus transition

---

## Let's Connect

I'm actively looking for full-time roles in **Data Science, Data Analytics, or Business Analytics** starting May 2026.

📧 abansal2@umassd.edu · 99anujbansal@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/anuj-bansal-854772189/)
💻 [GitHub](https://github.com/99anujb)
🌐 [Portfolio](https://portfolio-mu-inky-15.vercel.app)
