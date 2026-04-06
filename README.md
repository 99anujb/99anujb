# Hi, I'm Anuj Bansal 👋

**MS Data Science @ UMass Dartmouth** (GPA: 3.6 · Graduating May 2026)  
**B.Tech Mechanical Engineering** · Punjab Technical University  
📍 Dartmouth, Massachusetts · 📧 99anujbansal@gmail.com · 📞 (508) 965-2806  
🌐 **[portfolio-mu-inky-15.vercel.app](https://portfolio-mu-inky-15.vercel.app)**

---

## About Me

I'm a Data Scientist and ML practitioner with a unique combination of **4+ years of business analytics experience** and **graduate-level ML research** in scientific imaging. My background spans predictive modeling, customer analytics, deep learning, and production deployment — and I bring a rare ability to connect technical ML work to real business outcomes.

Highlights:
- 3rd Place, Graduate Poster — ASEE NE Section Conference 2026 (deep learning research on AFM surface reconstruction)
- Built a 17.3M-parameter Attention U-Net achieving **92.7% median height recovery** on nanoscale surface prediction
- Quantified **$4.1M in revenue at risk** via CLV modeling; secured **$3M in investment** through data-driven valuation
- Projected **$1.2M in incremental revenue** via KPI funnel analysis; identified **$2M in M&A synergies**

I'm actively seeking **Data Scientist, ML Engineer, or Data Analyst** roles starting May 2026.

---

## What I'm Building

| Project | Description | Stack | Status |
|--------|-------------|-------|--------|
| 🔬 [AFM Height Map Reconstruction](https://github.com/99anujb/AFM-Height-Reconstruction-DL) | Two-stage DL pipeline reconstructing nanoscale AFM surface height maps using a Size-Conditioned Attention U-Net — 92.7% height recovery, 0.80 nm MAE, 3rd Place ASEE NE 2026 | PyTorch, ResNet18, Attention U-Net, Custom Loss | ✅ Complete |
| 📉 [ChurnShield AI](https://github.com/99anujb/ChurnShield-AI) | End-to-end churn system: Optuna-tuned XGBoost (0.8493 ROC-AUC, 76% recall), K-Means segmentation, CLV modeling ($4.1M at risk), Kaplan-Meier survival analysis — live Streamlit dashboard | XGBoost, Optuna, SHAP, K-Means, Lifelines, Streamlit | ✅ Complete |
| 🏥 [Healthcare Disease Risk Prediction](https://github.com/99anujb/Healthcare-Disease-Risk-Prediction) | Multi-disease patient risk scoring system (Heart Disease, Diabetes, Chronic Kidney Disease) with SHAP explainability, calibrated risk scores, and interactive what-if simulator for clinical decision support | Scikit-learn, SHAP, Streamlit | ✅ Complete |
| 📈 [Stock Price Prediction Dashboard](https://github.com/99anujb) | Real-time ML dashboard fetching live market data via Alpaca API, engineering 14 technical indicators, predicting next-day prices for 5 major stocks (~1-2% MAE) with SHAP per-prediction explainability | Random Forest, SHAP, Alpaca API, Streamlit | ✅ Complete |
| 🎵 [Hybrid Music Recommendation System](https://github.com/99anujb) | Hybrid recommender on 93,185 Spotify tracks combining content-based KNN filtering with XGBoost popularity prediction (R² 0.474, 74% accuracy) via weighted hybrid scoring | XGBoost, Random Forest, KNN, scikit-learn | ✅ Complete |
| 🍽️ [Zomato Restaurant Rating Prediction](https://github.com/99anujb) | End-to-end ML pipeline on 71,730 records predicting restaurant ratings using Extra Trees Regressor — includes full EDA, Flask web app for live predictions, and complete system design documentation | Extra Trees, Random Forest, Flask, scikit-learn | ✅ Complete |
| 🌍 [Sustainable Fashion Trends Dashboard](https://github.com/99anujb) | Interactive D3.js data visualization dashboard exploring 5,000 fashion brand records across 10 countries (2010–2024) — choropleth maps, bubble overlays, animated year playback, and country-level drill-down charts | D3.js, TopoJSON, Vanilla JS, HTML/CSS | ✅ Complete |
| 🗃️ [Interactive Document Visualization Tool](https://github.com/99anujb) | Python ETL pipeline extracting 111 summaries from 5 U.S. intelligence agency text files (CIA, FBI, NSA, DIA, USCBP), powering an interactive D3.js frontend | Python, Pandas, D3.js, Sortable.js | ✅ Complete |
| 🤖 AI Research Agent | Autonomous agent that reads job descriptions, searches domain papers, and surfaces relevant insights | LangChain, OpenAI, Streamlit | 🔜 Coming Soon |
| 🔍 Fraud Detection Dashboard | Financial anomaly detection comparing classical vs neural approaches | Isolation Forest, Autoencoder, Plotly | 🔜 Coming Soon |

---

## Research Highlight — AFM Height Map Reconstruction

> **Deep Learning–Based Reconstruction of AFM Height Maps from TIFF Images Using a Size-Conditioned Attention U-Net**  
> UMass Dartmouth · Department of Data Science · Advisor: Dr. Vijaya Chalivendra  
> **3rd Place — ASEE NE Section Conference, 2026**

A two-stage deep learning pipeline for automated surface topography prediction:

- **Stage 1 — SizeRegressor** (ResNet18, 1.6M params): Predicts AFM scan dimensions from TIFF images · ~77% accuracy · 5.15 µm MAE
- **Stage 2 — Attention U-Net** (15.7M params): Reconstructs Z-height maps conditioned on predicted scan size · **92.7% median height recovery · 0.80 nm MAE** — ~70-point improvement over baseline
- Dataset: 79 original AFM scans augmented to 504 training pairs across 7 scan sizes (1–80 µm²) with group-based anti-leakage splits
- Custom **AFMLoss** function: L1 (0.6) + Std (0.3) + Range (0.1) components
- Outputs: XYZ point cloud files + Ra/Rq/Rz surface roughness metrics

---

## Professional Background

Before my MS, I spent 4+ years in data-driven business roles at fast-growing EdTech companies in India:

- **Scaler Academy** (Sr. Business Development Associate) — Built Python predictive models (22% lead scoring lift, 15% conversion boost); K-Means segmentation on 12,000+ prospects (18% email response lift); automated KPI dashboards in Tableau/Power BI saving 10 hrs/week; helped secure $3M in investment through data-driven valuation scenarios
- **Unacademy** (Business Development Associate) — CLV and churn models forecasting 6-month revenue for a $5M portfolio; A/B testing across 3,000 contacts (+9% conversion); audience segmentation driving 14% campaign ROI lift
- **Vedantu** (Business Development Representative) — M&A due diligence identifying $2M in synergies; SQL-driven reporting improving accuracy by 30% and cutting turnaround from 48h to 12h; Tableau dashboards accelerating decision cycles by 20%
- **GATES India** (Production Enhancement Assistant) — Time series analysis for labor allocation; statistical bottleneck analysis in manufacturing

---

## Technical Skills

**Languages & Querying**  
Python · SQL · JavaScript · R

**ML & Deep Learning**  
Scikit-learn · XGBoost · PyTorch · CNNs · Attention U-Net · ResNet · Transfer Learning · Custom Loss Functions · Hyperparameter Tuning (Optuna) · Survival Analysis (Kaplan-Meier, Cox PH)

**Data & EDA**  
Pandas · NumPy · Feature Engineering · Data Cleaning · Statistical Modeling · ETL Pipelines · Data Mining

**Explainability & Analytics**  
SHAP (TreeExplainer, KernelExplainer) · A/B Testing · Funnel & Cohort Analysis · KPI Tracking · Churn Modeling · CLV · Revenue Forecasting · Financial Modeling

**Visualization & BI**  
Tableau · Power BI · Matplotlib · Seaborn · Plotly · D3.js

**Scientific Computing**  
OpenCV · AFM Image Processing · Z-Height Map Analysis · Image Normalization · Numerical Computing

**Tools & Deployment**  
Jupyter · Git · GitHub · VS Code · Flask · FastAPI · Streamlit · Docker · AWS (S3, EC2) · GitHub Pages

---

## Education

🎓 **MS Data Science** — University of Massachusetts Dartmouth (May 2026)  
GPA: 3.6 · Coursework: Machine Learning, Deep Learning, Data Mining, Statistical Methods, Business Analytics, Database Management, Cloud Computing (AWS), Data Visualization

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

I'm actively looking for full-time roles in Data Science, ML Engineering, or Data Analytics starting May 2026.

📧 abansal2@umassd.edu · 99anujbansal@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/anuj-bansal-854772189/)  
💻 [GitHub](https://github.com/99anujb)  
🌐 [Portfolio](https://portfolio-mu-inky-15.vercel.app)
