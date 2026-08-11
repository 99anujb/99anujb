# Hi, I'm Anuj Bansal 👋

**Data Analyst** · MS Data Science, UMass Dartmouth (GPA 3.6 · completed May 2026)
📍 Dartmouth, Massachusetts · 📧 [99anujbansal@gmail.com](mailto:99anujbansal@gmail.com)
🌐 **[Portfolio](https://portfolio-mu-inky-15.vercel.app)** · 🔗 **[LinkedIn](https://www.linkedin.com/in/anuj-bansal-854772189/)**

---

## About Me

Data analyst with **four years in EdTech growth analytics** at SoftBank- and Sequoia-backed platforms in India, building the SQL, dashboards and executive reporting that sales and leadership teams ran on day to day. I then completed an **MS in Data Science at UMass Dartmouth (May 2026)**, with a year of applied research analytics alongside it.

The work I'm best at sits where messy source data has to become reporting people actually trust — funnel and cohort analysis, CRM and ERP data modeling, and the data-quality work underneath the dashboards.

**Selected results**
- Funnel analysis across 8 core KPIs; recommendations projected **$1.2M in incremental revenue**
- Python lead-scoring models that lifted **conversion 15%**; K-Means segmentation across 12,000+ prospects lifting **email response 18%**
- SQL reporting pipelines that cut turnaround from **48 hours to 12**
- **3rd Place, Graduate Poster — ASEE Northeast 2026**, for deep learning research on AFM surface reconstruction

**Open to Data Analyst, Business Analyst and Data Scientist roles** — onsite, hybrid or remote across the US.

---

## Experience

**Research Assistant — Data Analysis** · University of Massachusetts Dartmouth · *Jun 2025 – May 2026*
Built the Power BI and Tableau reporting the research team ran on — per-group error breakdowns and run-over-run comparisons in one view. Traced a silent data-quality defect (an axis-alignment mismatch between coordinate files and image rows) that had capped measured accuracy across the entire dataset. Designed the validation scheme: group-based splits that eliminated leakage. Built the two-stage PyTorch reconstruction pipeline that won 3rd Place at ASEE NE 2026.

**Senior Growth Analyst** · Scaler Academy, Bengaluru · *Jun 2022 – Sep 2023*
*Tech upskilling platform; ~$710M valuation, backed by Sequoia India, Tiger Global and Lightrock.*
Owned the monthly executive deck off an 8-KPI funnel analysis. Automated KPI extraction through ETL pipelines and authored the Power BI data model, DAX measures and Power Query transformations behind the leadership dashboards — reporting latency went from weekly to daily across 15+ product lines.

**Growth Analyst** · Unacademy, Bengaluru · *Apr 2021 – May 2022*
*India's largest online learning platform; $3.4B valuation, backed by SoftBank Vision Fund, Temasek and General Atlantic.*
Modeled LeadSquared CRM data in Power BI to report retention, capacity and productivity across a $5M product portfolio, replacing a recurring manual spreadsheet process. Ran A/B tests on outreach scripts across 3,000 contacts (+9% conversion).

**Business Analyst** · Vedantu, Gurugram · *Jan 2020 – May 2021*
*Live online tutoring platform; ~$600M valuation and 30M+ monthly users during tenure, backed by Tiger Global and GGV Capital.*
Wrote complex SQL (joins, CTEs, window functions) to clean, transform and validate datasets for downstream reporting. Built Tableau dashboards for sales leadership and documented how reporting data flowed from Oracle ERP and CRM sources, so leadership knew which numbers were certified.

---

## Projects

| Project | What it does | Stack |
|---|---|---|
| 📊 [S&P 500 Sector Intelligence](https://github.com/99anujb/sp500-sector-intelligence) | Tableau dashboard over **619K** daily price/volume records across 11 GICS sectors (2013–2018) — KPI tiles, annual heatmap, risk-vs-return scatter, custom Python data-prep pipeline | Tableau, Python, Pandas |
| 📉 [ChurnShield AI](https://github.com/99anujb/customer-churn-prediction) | Retention system on 7,043 telecom records: Optuna-tuned XGBoost (0.8493 ROC-AUC), Kaplan-Meier + Cox PH survival curves, K-Means segmentation, CLV modeling putting **$4.1M** of revenue at risk and tracing **$262K** to quiet churners the classifier missed | XGBoost, Optuna, Lifelines, SHAP, Streamlit |
| 🔬 [AFM Height Map Reconstruction](https://github.com/99anujb/AFM-Height-Reconstruction-DL) | Two-stage deep learning pipeline reconstructing nanoscale surface height maps via a size-conditioned Attention U-Net — **97.1% median recovery, 0.77 nm MAE**, 3rd Place ASEE NE 2026 | PyTorch, ResNet18, Attention U-Net |
| 🏥 [Healthcare Disease Risk Prediction](https://github.com/99anujb/Healthcare-Disease-Risk-Prediction) | Multi-disease risk scoring (heart, diabetes, CKD) with stacking ensembles, calibrated probabilities, SHAP explainability, Fairlearn bias audits and a what-if simulator | scikit-learn, SHAP, Fairlearn, Streamlit |
| 🎵 [Hybrid Music Recommender](https://github.com/99anujb/HybridMusicRecommender) | Recommender over **169K** Spotify tracks blending XGBoost popularity prediction (R²=0.47) with KNN cosine similarity across 9 audio features | XGBoost, KNN, scikit-learn, Streamlit |
| 📈 [StockSense](https://github.com/99anujb/stocksense) | Real-time dashboard pulling live market data via Alpaca API, engineering 14 technical indicators, predicting next-day prices for 5 stocks (~1–2% MAE) with per-prediction SHAP | Random Forest, SHAP, Alpaca API, Streamlit |
| 🌍 [Sustainable Fashion Trends](https://github.com/99anujb/sustainable-fashion-viz) | Interactive D3.js dashboard over 5,000 brand records across 10 countries (2010–2024) — choropleth maps, animated year playback, country drill-down | D3.js, TopoJSON, Python ETL |
| 🍽️ [Zomato Rating Predictor](https://github.com/99anujb/zomato-rating-predictor) | End-to-end pipeline on 71,730 records predicting restaurant ratings, deployed as a Flask app | Extra Trees, Flask, scikit-learn |
| 🗃️ [Declassified Docs Explorer](https://github.com/99anujb/declassified-docs-explorer) | Python ETL extracting 111 summaries from 5 US intelligence agency sources, powering a D3.js frontend with live search | Python, Pandas, D3.js |
| 🎨 [3D Portfolio](https://github.com/99anujb/Portfolio) | Interactive 3D portfolio site — React + Three.js scenes, GSAP animations, Rapier physics | React, Three.js, GSAP, Vercel |

---

## Research — AFM Height Map Reconstruction

> **Deep Learning–Based Reconstruction of AFM Height Maps from TIFF Images Using a Size-Conditioned Attention U-Net**
> UMass Dartmouth · Advisor: Dr. Vijaya Chalivendra · **3rd Place, ASEE Northeast Section Conference 2026**

- **Stage 1 — SizeRegressor** (ResNet18): predicts AFM scan dimensions from TIFF images · 75.8% accuracy, 3.03 µm MAE
- **Stage 2 — Size-Conditioned Attention U-Net** (FiLM conditioning at every decoder level): reconstructs Z-height maps · **97.1% median height recovery, 0.77 nm MAE** — a 75-point gain over baseline
- Custom **AFMLoss v2** (0.5·L1 + 0.3·Std + 0.2·Range) to prevent blurry mean predictions and enforce correct dynamic range
- Group-based anti-leakage splits across 7 scan-size groups (1–80 µm²); outputs Gwyddion-compatible XYZ point clouds plus Ra/Rq/Rz roughness metrics

---

## Technical Skills

**Data Analysis** — SQL (joins, CTEs, window functions) · Python (Pandas, NumPy) · Advanced Excel (pivot tables, Power Query) · A/B and hypothesis testing · cohort and funnel analysis · forecasting and KPI tracking

**Visualization & BI** — Tableau · Power BI (data modeling, DAX, Power Query) · D3.js · Plotly · Streamlit · executive reporting and data storytelling

**Machine Learning** — scikit-learn · XGBoost · LightGBM · K-Means · survival analysis (Kaplan-Meier, Cox PH) · Optuna · SHAP · Fairlearn

**Deep Learning** — PyTorch · CNNs · U-Net · attention mechanisms · ResNet · transfer learning · custom loss functions

**Data Platforms** — MySQL · PostgreSQL · SQL Server · Oracle ERP · LeadSquared CRM · Workday · AWS (S3, EC2)

**Engineering** — ETL pipelines · Git/GitHub · Flask · FastAPI · Docker · Jupyter · VS Code

---

## Education

🎓 **MS Data Science** — University of Massachusetts Dartmouth · *Sep 2024 – May 2026* · GPA 3.6
Coursework: Business Intelligence, Data Visualization, Database Management, Statistical Methods, Big Data Analytics, Data Mining, Machine Learning, Deep Learning, Cloud Computing (AWS)

📚 **Data Science & Machine Learning Program** — Scaler Academy · *Sep 2023 – Sep 2024*

🎓 **B.Tech Mechanical Engineering** — Punjab Technical University · *Jul 2016 – Jun 2020*

---

## Leadership

**Treasurer & Executive Board Member** — Indian Student Association, UMass Dartmouth
Led **$20,000+** in fundraising · organized cultural events for 300+ attendees

**Student Ambassador** — International Student & Scholar Center, UMass Dartmouth
Mentored incoming international students through academics and campus transition

---

## Let's Connect

Open to **Data Analyst, Business Analyst and Data Scientist** roles across the US. Available immediately.

📧 [99anujbansal@gmail.com](mailto:99anujbansal@gmail.com) · 🔗 [LinkedIn](https://www.linkedin.com/in/anuj-bansal-854772189/) · 🌐 [Portfolio](https://portfolio-mu-inky-15.vercel.app)
