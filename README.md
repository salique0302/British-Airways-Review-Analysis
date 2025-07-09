# ✈️ British Airline Review Sentiment Analysis

This project scrapes customer reviews for British Airways from [airlinequality.com](https://www.airlinequality.com/airline-reviews/british-airways), processes the text using NLP techniques, and performs sentiment analysis to assess overall passenger satisfaction. It includes data extraction, transformation, and visualization stages to uncover insights from user-generated reviews.

---

## 📌 Features

- ✅ Web scraping using `requests` and `BeautifulSoup`
- 🔄 Data cleaning & preprocessing: lowercasing, punctuation removal, stopwords filtering
- 🧠 Sentiment scoring using `TextBlob`
- 📊 Visual analytics: rating distribution, sentiment trends, correlation heatmaps
- 📁 Exportable cleaned dataset for downstream tasks

---

## 📂 Project Structure

```
Review Analysis.ipynb      # Jupyter notebook with full pipeline
```

---

## ⚙️ Tech Stack

- Python
- Jupyter Notebook
- BeautifulSoup
- pandas, numpy
- TextBlob
- seaborn, matplotlib

---

## 🧪 Steps Performed

### 1. Extract
- Scraped 37 pages of British Airways reviews
- Collected review titles, texts, and star ratings

### 2. Transform
- Cleaned and tokenized text
- Removed stopwords and punctuation
- Calculated sentiment polarity scores

### 3. Load & Analyze
- Visualized rating vs sentiment polarity
- Exported final dataframe for use in ML or BI tools

---

## 📈 Sample Outputs

- Histogram of sentiment polarity
- Bar plot of average rating per sentiment group
- Word cloud for common terms

---

## 🚀 How to Run

1. Clone the repo or download the notebook
2. Install required libraries:

```bash
pip install requests beautifulsoup4 pandas numpy seaborn matplotlib textblob
```

3. Open the notebook and run all cells
4. Modify `base_url` and `pages` to scrape other airlines if needed

---

## 🧠 Future Improvements

- Use spaCy or BERT for more advanced sentiment modeling
- Add named entity recognition (NER) to highlight airline-specific issues
- Deploy as a Streamlit app for interactive use

---

## 👤 Author

Developed by MD Salique for NLP & Web Scraping practice 🚀

---
