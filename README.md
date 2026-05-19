# SentimentIQ — MockShop Review Dashboard

> School project: Text Classification & Sentiment Analysis Pipeline  
> Live dashboard powered by VADER sentiment scoring — no backend needed.

## 🌐 Live Demo

**[View Dashboard →](https://meitantehizumii.github.io/sentimentanalysis/)**  
**[View MockShop Product Page →](https://meitantehizumii.github.io/sentimentanalysis/mockshop_product.html)**

---

## 📁 Files

| File | Description |
|------|-------------|
| `index.html` | Main sentiment analysis dashboard |
| `mockshop_product.html` | Fake Shopee-like product page with 20 reviews |
| `SentimentIQ_MockShop.ipynb` | Jupyter notebook (local Python pipeline) |

---


## 🧠 How the Sentiment Engine Works

```
Review Text + Star Rating
        │
        ▼
  Word-level VADER scoring
  (lexicons + intensifiers + negators + caps boost)
        │
        ▼
  65% VADER compound  +  35% Star rating signal
        │
        ▼
  Label: Positive / Negative / Neutral / Mixed
  + Confidence %, Categories, Intents, Dimensions
```

---

## ✍️ Live Comment Feature

- Type any review → pick stars → **Analyze & Submit**
- VADER scores it instantly in the browser
- All KPIs, charts, and table update in real time
- Toast notification shows the detected sentiment

---

*Built for school project purposes. Not affiliated with Shopee.*
