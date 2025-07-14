# 📊 Sentiment Analysis Dashboard – Insurance Customer Reviews (Power BI)

This Power BI project analyzes customer feedback for an insurance company using sentiment analysis and natural language processing (NLP) techniques.

The dashboard presents overall sentiment trends, highlights key topics from customer reviews using word clouds, and helps stakeholders identify areas for service improvement.

---

## 🔍 Key Features

- **Sentiment Breakdown**: Visual representation of positive, neutral, and negative reviews.
- **Trends Over Time**: Track how customer sentiment changes across months.
- **Word Cloud**: Extract and display the most frequent keywords in feedback.
- **Category Filters**: Drill down by product type, region, or channel (if available).
- **Review Count & Rating Distribution**: Understand volume and distribution of reviews.

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `SentimentDashboard.pbix` | The main Power BI report |
| `data/customer_reviews.csv` | Source dataset with customer reviews and sentiment scores |
| `README.md` | Project overview and instructions (this file) |

---

## 📊 Dataset Overview

- **Source**: Internal customer reviews (anonymized)
- **Columns**:
  - `ReviewText` – Free-text customer feedback
  - `SentimentScore` – Assigned sentiment (Positive, Neutral, Negative)
  - `Date` – Date of the review
  - *(Optional)* `ProductType`, `Region`, `Channel`, etc.

---

## 🚀 How to Use

1. Open `SentimentDashboard.pbix` in **Power BI Desktop**.
2. If using local data, ensure the CSV file path is correctly mapped.
3. Explore the visuals using slicers and filters for deeper insights.
4. Use the Word Cloud to explore commonly used terms in reviews.

---

## 💡 Business Value

This dashboard helps the insurance company:
- Monitor customer satisfaction levels
- Detect negative trends early
- Identify frequently mentioned issues and strengths
- Guide customer service and product strategy improvements

---

## 📌 Notes

- This project uses basic NLP techniques; for production, more advanced models like BERT or Azure Cognitive Services could be integrated.
- No personally identifiable information (PII) is included in the data.

---

