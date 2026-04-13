# 📊 Social Media Campaign Performance & ROI Analysis

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-yellow)
![XGBoost](https://img.shields.io/badge/XGBoost-71.55%25-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 🎯 Project Overview
An end-to-end data science project analyzing **300,000+ social media ad campaigns** across Instagram, Facebook, Twitter, and Pinterest. The project identifies ROI drivers, audience insights, and predicts campaign success using Machine Learning.

**Key Finding:** Pinterest delivers **5.6x lower ROI** than Instagram. Reallocating budget to Instagram could unlock significantly higher returns.

---

## 📌 Business Problem
A brand runs paid campaigns across multiple social media platforms but doesn't know:
- Which platform gives the best ROI?
- Which audience segment converts most?
- Which campaign type is most successful?
- Can we predict if a campaign will succeed before spending budget?

---

## 🔍 Key Insights

| Insight | Finding |
|---|---|
| Best Channel | Instagram (ROI: 4.01) |
| Worst Channel | Pinterest (ROI: 0.72) |
| Best Campaign Goal | Product Launch |
| Best Audience | All Ages segment |
| Best Month | April |
| Best Day | Friday |
| Total Revenue Analyzed | $9.71 Billion |
| Total Ad Spend Analyzed | $2.33 Billion |
| Overall Average ROI | 3.18x |

---

## 🤖 Machine Learning Results

| Model | Accuracy | AUC Score |
|---|---|---|
| Logistic Regression | ~58% | ~0.65 |
| Random Forest | ~69% | ~0.77 |
| **XGBoost** | **71.55%** | **0.80** |

**XGBoost** was the best performing model with:
- 71.55% Accuracy
- 0.80 AUC Score
- Trained on 240,000 samples
- Tested on 60,000 samples

---

## 📊 Dashboard Preview

### Page 1 — Campaign Overview
![Dashboard Page 1](images/dashboard_page1.png)

### Page 2 — Channel & Audience Analysis
![Dashboard Page 2](images/dashboard_page2.png)

### Page 3 — ML Predictions
![Dashboard Page 3](images/dashboard_page3.png)

---

## 🛠️ Tech Stack

| Tool | Usage |
|---|---|
| Python | Data cleaning, EDA, ML |
| Pandas & NumPy | Data manipulation |
| Matplotlib & Seaborn | Data visualization |
| Scikit-learn | ML models |
| XGBoost | Best ML model |
| MySQL | Data storage |
| Power BI | Interactive dashboard |
| Jupyter Notebook | Development environment |

---

## 📁 Project Structure

social-media-campaign-analysis/
├── data/                    # Raw and cleaned datasets
├── notebooks/               # Jupyter notebooks
│   ├── data_loading_and_exploration.ipynb
│   ├── EDA_Analysis.ipynb
│   └── ML_Model.ipynb
├── models/                  # Saved ML models
├── dashboard/               # Power BI files
├── images/                  # Charts and visualizations
├── powerbi_exports/         # CSV files for Power BI
└── README.md

---

## 🚀 How to Run

**1. Clone the repository:**
```bash
git clone https://github.com/Lovepreet1121/social-media-campaign-analysis.git
cd social-media-campaign-analysis
```

**2. Install dependencies:**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost jupyter
```

**3. Download dataset:**
- Get dataset from [Kaggle](https://www.kaggle.com/datasets/jsonk11/social-media-advertising-dataset)
- Place in `data/` folder

**4. Run notebooks in order:**
data_loading_and_exploration.ipynb
EDA_Analysis.ipynb
ML_Model.ipynb

**5. Open Power BI Dashboard:**
- Open `dashboard/Social_Media_Campaign_Analysis.pbix`

---

## 💡 Business Recommendations

1. **Reallocate Pinterest budget** → Move to Instagram for 5.6x better ROI
2. **Focus on Product Launch campaigns** → Highest success rate
3. **Target All Ages segment** → Consistently highest ROI
4. **Run campaigns in April** → Best monthly performance
5. **Schedule campaigns on Fridays** → Best day for engagement
6. **Use ML predictions** → Pre-screen campaigns before spending budget

---

## 📈 Resume Impact

This project demonstrates:
- ✅ End-to-end data pipeline (300K+ records)
- ✅ Advanced EDA and business insights
- ✅ Machine Learning with 71.55% accuracy
- ✅ Interactive Power BI dashboard
- ✅ Real business recommendations

---

## 👤 Author

**Lovepreet**
- GitHub: [github.com/Lovepreet1121](https://github.com/Lovepreet1121)
- LinkedIn: [linkedin.com/in/love-preet-/](https://linkedin.com/in/love-preet-/)
- Email: lp5120452@gmail.com

