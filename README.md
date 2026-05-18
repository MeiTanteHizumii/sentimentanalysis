# SentimentIQ — MockShop Review Dashboard

> School project: Text Classification & Sentiment Analysis Pipeline  
> Live dashboard powered by VADER sentiment scoring — no backend needed.

## 🌐 Live Demo

**[View Dashboard →](https://YOUR-USERNAME.github.io/sentimentiq/)**  
**[View MockShop Product Page →](https://YOUR-USERNAME.github.io/sentimentiq/mockshop_product.html)**

---

## 📁 Files

| File | Description |
|------|-------------|
| `index.html` | Main sentiment analysis dashboard |
| `mockshop_product.html` | Fake Shopee-like product page with 20 reviews |
| `SentimentIQ_MockShop.ipynb` | Jupyter notebook (local Python pipeline) |

---

## 🚀 Publishing to GitHub Pages (3 steps)

### Step 1 — Create a GitHub repository
1. Go to [github.com](https://github.com) → **New repository**
2. Name it `sentimentiq`
3. Set it to **Public**
4. Click **Create repository**

### Step 2 — Upload the files
1. Click **Add file → Upload files**
2. Upload all three files:
   - `index.html`
   - `mockshop_product.html`
   - `SentimentIQ_MockShop.ipynb`
3. Click **Commit changes**

### Step 3 — Enable GitHub Pages
1. Go to **Settings → Pages**
2. Under **Source**, select **Deploy from a branch**
3. Branch: `main` | Folder: `/ (root)`
4. Click **Save**
5. Wait ~60 seconds, then visit:
   `https://YOUR-USERNAME.github.io/sentimentiq/`

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
