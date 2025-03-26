# 🎵 Are Shorter Songs More Popular?  
**Spotify Song Trend Analysis (1986–2023)**

This project explores whether shorter song durations are associated with higher popularity on streaming platforms — with a special focus on Spotify. Using 17,000+ tracks and audio features like energy, danceability, and tempo, we examined the impact of song duration on listener engagement and forecasted future song length trends.

---

## 📌 Overview

With the rise of streaming and platforms like TikTok promoting shorter content, we asked:

> **Are shorter songs more likely to be popular?**

To answer this, we combined data science with music industry context to assess how song characteristics impact popularity and what this means for producers, platforms, and consumers.

---

## 🧪 Methods

- **Data Cleaning**: Removed outliers, dropped nulls, filtered key columns  
- **EDA**: Trend analysis of song length and popularity by year  
- **Correlation Heatmap**: Examined relationships between variables  
- **Simple Linear Regression**: Popularity vs. song duration  
- **PCA**: Reduced dimensionality of ~20 audio features  
- **Multiple Regression**: Identified drivers of popularity  
- **Trend Forecasting**: Predicted average song duration to 2050  

---

## 📊 Key Findings

- 📉 **Negative correlation** between duration and popularity (r = -0.15)  
- ⏱️ **Each minute increase** in duration leads to ~1.55 point **drop** in popularity score  
- 📈 Song durations have **declined from ~4.3 min to under 3.3 min** since the 1990s  
- 🧠 PCA & regression reveal artist popularity (followers) and loudness as additional predictors  
- 🔮 **Predicted avg. song duration in 2040: ~2.92 min**

---

## 🧠 Business Implications

- Streaming algorithms may favor **shorter songs** to boost play counts
- **Artists & producers** should consider optimizing song length to match listener behavior
- Platforms can **adjust recommendation models** to balance engagement with content variety

---

## 📁 Files in This Repository

| File Name                           | Description                                     |
|------------------------------------|-------------------------------------------------|
| `Spotify_Popularity_Analysis.ipynb`| Full code: data cleaning, analysis, modeling    |
| `Shorter_Songs_Trend_Report.pdf`   | Final slide deck summary with business insights |

---

## 💻 Tech Stack

- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- **Spotify API / Kaggle Dataset**
- **PCA**, **Linear Regression**, **Multiple Regression**

---

## 🧠 Author

Prepared by: **Yi-Chieh (Bella) Kuo**  
📍 Los Angeles, CA
🎓 USC MSBA 2023
📧 yichiehk@marshall.usc.edu 
🔗 [LinkedIn](https://www.linkedin.com/in/yi-chieh-kuo/)
