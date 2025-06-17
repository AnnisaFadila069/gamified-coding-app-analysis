# NLP-Based Analysis of Gamified Coding Apps for Middle School

This repository contains the code and resources for a research project that analyzes user reviews of gamified coding applications targeted at middle school students. The analysis uses Natural Language Processing (NLP) techniques to evaluate user sentiment, extract dominant topics, and compare app features to provide strategic recommendations for educational use.

## 📚 Project Background

With the increasing integration of programming into early education, many gamified apps have emerged to teach coding to students in an interactive way. This project aims to:

- Scrape and process user reviews from Google Play Store
- Perform sentiment analysis using TextBlob and VADER
- Identify key topics discussed in reviews via topic modeling (LDA)
- Benchmark apps based on features and user feedback
- Cluster apps by similarity to provide educational recommendations

## 🔍 Target Applications

The following coding education apps were selected based on expert-curated recommendations:
- Mimo
- Sololearn
- Programming Hub
- Sphero Edu
- Codecademy Go

Sources for selection:
- Common Sense Education: [Best Coding Tools for Middle School](https://www.commonsense.org/education/lists/best-coding-tools-for-middle-school)
- Teach Your Kids Code: [Coding Apps for Kids](https://teachyourkidscode.com/best-coding-apps-for-kids/)
- Codeyoung: [25 Best Coding Apps for Kids](https://www.codeyoung.com/blog/best-coding-apps-for-kids)

## ⚙️ Features

- ✅ Data scraping using `google-play-scraper`
- ✅ Text preprocessing with `nltk`, `contractions`, `spacy`
- ✅ Sentiment analysis via `TextBlob` and `VADER`
- ✅ Topic modeling with LDA (`scikit-learn`)
- ✅ App clustering with K-Means
- ✅ WordCloud and visualization using `matplotlib` & `seaborn`

## 🧪 Installation

Clone the repository and install dependencies:
```bash
git clone https://github.com/AnnisaFadila069/gamified-coding-app-analysis
cd coding-app-review-nlp
pip install -r requirements.txt
```
Also run:
```bash
python -m nltk.downloader vader_lexicon
python -m textblob.download_corpora
python -m spacy download en_core_web_sm
```

## 📁 Project Structure
```bash
📦 coding-app-review-nlp
├── data/                    # Raw and processed review data
├── src/                     # Scripts for preprocessing, analysis, visualization
├── notebooks/               # Jupyter notebooks for step-by-step experimentation
├── requirements.txt
├── README.md
```
