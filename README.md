# Hi, I'm Anuj Bansal 👋

**MS Data Science @ UMass Dartmouth** (GPA: 3.6 · Graduating May 2026)  
**B.Tech Mechanical Engineering** · Punjab Technical University  
📍 Dartmouth, Massachusetts · 📧 abansal2@umassd.edu · 📞 (508) 965-2806

---

## About Me

I'm a Data Scientist and ML practitioner with a unique combination of **4+ years of business analytics experience** and **graduate-level ML research** in scientific imaging. My background spans predictive modeling, customer analytics, and deep learning — and I bring a rare ability to connect technical ML work to real business outcomes.

Currently, I'm leading a research project at UMass Dartmouth applying deep learning to **Atomic Force Microscopy (AFM) surface reconstruction** — building models that predict nanoscale surface topography from image inputs, with applications in materials science and semiconductor manufacturing.

I'm actively seeking **Data Scientist, ML Engineer, or Data Analyst** roles starting May 2026.

---

## What I'm Building

| Project | Description | Stack | Status |
|--------|-------------|-------|--------|
| 🔬 [AFM Height Map Reconstruction](https://github.com/99anujb/AFM-Height-Reconstruction-DL) | Deep learning pipeline reconstructing nanoscale surface height maps from AFM TIFF images using a Size-Conditioned Attention U-Net | PyTorch, ResNet18, U-Net, Python | ✅ Complete |
| 📉 Customer Churn Prediction | End-to-end churn prediction with SHAP explainability — live Streamlit app | XGBoost, SHAP, Streamlit | 🔨 In Progress |
| 🏥 Healthcare Risk Prediction | Patient disease risk scoring dashboard with what-if analysis | Scikit-learn, SHAP, Streamlit | 🔜 Coming Soon |
| 🤖 AI Research Agent | Autonomous agent that reads job descriptions, searches domain papers, and surfaces relevant insights | LangChain, OpenAI, Streamlit | 🔜 Coming Soon |
| 🔍 Fraud Detection Dashboard | Financial anomaly detection comparing classical vs neural approaches | Isolation Forest, Autoencoder, Plotly | 🔜 Coming Soon |

---

## Research Highlight — AFM Height Map Reconstruction

> **Deep Learning–Based Reconstruction of AFM Height Maps from TIFF Images Using a Size-Conditioned Attention U-Net**  
> UMass Dartmouth · Department of Data Science · Advisor: Dr. Vijaya Chalivendra

A two-stage deep learning pipeline for automated surface topography prediction:

- **Stage 1 — SizeRegressor** (ResNet18, 1.6M params): Predicts AFM scan dimensions from TIFF images · ~77% accuracy · 5.15 µm MAE
- **Stage 2 — Attention U-Net** (15.7M params): Reconstructs Z-height maps conditioned on predicted scan size · **89% median height recovery · 1.08 nm MAE**
- Dataset: 79 original AFM scans augmented to 504 training pairs across 7 scan sizes (1–80 µm²)
- Custom **AFMLoss** function: L1 (0.6) + Std (0.3) + Range (0.1) components
- Outputs: XYZ point cloud files + Ra/Rq/Rz surface roughness metrics
- Presented at **ASEE NE Section Conference, March 2026**

---

## Professional Background

Before my MS, I spent 4+ years in data-driven business roles at fast-growing EdTech companies in India:

- **Scaler Academy** (Sr. Business Development Associate) — Built Python predictive models for lead scoring; automated KPI dashboards in Tableau/Power BI saving 10 hrs/week of manual reporting
- **Unacademy** (Business Development Associate) — Churn analysis, CLV modeling, A/B testing on outreach campaigns
- **Vedantu** (Business Development Representative) — Audience segmentation, revenue forecasting, cross-functional reporting
- **GATES India** (Production Enhancement Assistant) — Time series analysis for labor allocation; statistical bottleneck analysis in manufacturing

---

## Technical Skills

**Languages & Querying**  
Python · SQL · JavaScript

**ML & Deep Learning**  
Scikit-learn · XGBoost · PyTorch · CNN Architectures · Attention U-Net · ResNet · Model Evaluation · Loss Function Design

**Data & EDA**  
Pandas · NumPy · Feature Engineering · Data Cleaning · Statistical Modeling · Data Mining

**Explainability & Analytics**  
SHAP · A/B Testing · Funnel Analysis · KPI Tracking · Churn Analysis · CLV · Revenue Forecasting

**Visualization & BI**  
Tableau · Power BI · Matplotlib · Seaborn · Plotly · D3.js

**Scientific Computing**  
OpenCV · AFM Image Processing · Z-Height Map Analysis · Image Normalization · Numerical Computing

**Tools & Deployment**  
Jupyter · Git · VS Code · Flask · Streamlit · GitHub Pages · Excel

---

## Education

🎓 **MS Data Science** — University of Massachusetts Dartmouth (May 2026)  
GPA: 3.6 · Coursework: Machine Learning, Data Mining, Statistical Modeling, Business Analytics, Data Visualization

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

📧 abansal2@umassd.edu  
🔗 [LinkedIn](https://www.linkedin.com/in/anuj-bansal-854772189/)  
💻 [GitHub](https://github.com/99anujb)
