# 📱 Google Play Store Data Analytics Project

A complete end-to-end data analytics project analyzing **10,000+ apps** from the Google Play Store — built as a 12th grade student project using Excel, SQL, Python, and Power BI.

---

## 📌 Project Overview

This project explores the Google Play Store dataset to uncover meaningful patterns about app categories, ratings, pricing models, and installation trends — just like a real data analyst would.

| Detail | Info |
|--------|------|
| 📁 Dataset | Google Play Store Apps (Kaggle) |
| 📊 Rows | 10,841 (raw) → 8,196 (after cleaning) |
| 🛠️ Tools | Excel, SQL, Python, Power BI |
| 👩‍💻 Author | Gaayathri K G |
| 🎓 Grade | 12th Standard |

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| ![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=flat&logo=microsoft-excel&logoColor=white) | Data exploration and Pivot Tables |
| ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white) | Querying and extracting data |
| ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) | Data cleaning and visualization |
| ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black) | Interactive dashboard creation |

---

## 📂 Project Structure

```
GooglePlayStoreProject/
│
├── googleplaystore.csv          # Raw dataset (from Kaggle)
├── cleaned_playstore.csv        # Cleaned dataset (after Python processing)
├── playstore.db                 # SQLite database
│
├── playstore.ipynb              # Python Jupyter Notebook (cleaning + charts)
│
├── queries.sql                  # All 7 SQL queries
│
├── charts/
│   ├── chart1_top_categories.png
│   ├── chart2_rating_distribution.png
│   ├── chart3_free_vs_paid.png
│   └── chart4_heatmap.png
│
├── GooglePlatStore.pbix         # Power BI Dashboard (3 pages)
│
└── README.md
```

---

## 🔄 Project Phases

### Phase 1 — Understand the Data (Excel)
- Opened raw CSV and explored all 13 columns
- Created a Pivot Table showing app count per category
- Built a bar chart of top 10 categories

### Phase 2 — Query the Data (SQL)
Ran 7 SQL queries including:
- Top 10 categories by app count
- Average rating per category
- Free vs Paid app count
- Top 10 most reviewed apps
- Apps rated above 4.5

### Phase 3 — Clean & Analyze (Python)
- Removed missing values, duplicates, and errors
- Fixed column formats (Installs, Price, Reviews)
- Generated 4 analysis charts
- Ran a T-test to compare Free vs Paid ratings

### Phase 4 — Dashboard (Power BI)
Built a 3-page interactive dashboard:
- **Page 1:** Overview (Cards, Pie Chart, Bar Chart, Slicers)
- **Page 2:** Ratings & Reviews (Histogram, Bar Chart, Scatter Plot)
- **Page 3:** Installs Analysis (Bar Charts by App, Category, and Type)

---

## 📊 Python Charts

| Chart | Description |
|-------|-------------|
| `chart1_top_categories.png` | Top 10 app categories by count |
| `chart2_rating_distribution.png` | Distribution of app ratings |
| `chart3_free_vs_paid.png` | Free vs Paid comparison |
| `chart4_heatmap.png` | Correlation between numeric variables |

---

## 💡 Key Insights

1. **FAMILY** and **GAME** are the most populated categories with 1,800+ and 950+ apps respectively
2. The average app rating is **4.17/5** — most apps on the Play Store are well-rated
3. **92.63%** of apps are Free — developers prefer the freemium model
4. Apps with more reviews also tend to have more installs (positive correlation)
5. **Google and Facebook** apps dominate the top installs due to brand trust

---

## 🧪 Statistical Finding

A **T-test** was conducted to compare ratings of Free vs Paid apps.
- Result: **p < 0.05** → The difference is statistically significant
- Paid apps have a slightly higher average rating than Free apps

---

## ⚙️ How to Run

### Python Setup
```bash
pip install pandas matplotlib seaborn scipy jupyter
jupyter notebook
```

### Open the Notebook
```bash
cd GooglePlayStoreProject
jupyter notebook playstore.ipynb
```

### SQL Setup
1. Install [DB Browser for SQLite](https://sqlitebrowser.org)
2. Open `playstore.db`
3. Run queries from `queries.sql`

---

## 📦 Dataset

- **Source:** [Google Play Store Apps — Kaggle](https://www.kaggle.com/datasets/lava18/google-play-store-apps)
- **Author:** Lavanya Gupta
- **Size:** 10,841 rows × 13 columns

---

## 📋 Deliverables

- [x] Raw dataset CSV
- [x] Excel Pivot Table + Chart
- [x] SQL queries file (7 queries)
- [x] Python Jupyter Notebook
- [x] Cleaned dataset CSV
- [x] 4 Analysis Charts (PNG)
- [x] Power BI Dashboard (3 pages)
- [x] Final Report with Insights

---

## 👩‍💻 Author

**Gaayathri K G**  

🔗 [GitHub Profile](https://github.com/gaayathri26)

---

*This project was built as part of a 12th grade data analytics curriculum using real-world tools and a real dataset.*

