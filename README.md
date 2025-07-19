# 📱 App Review Scraper for Google Play & App Store

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![Platform](https://img.shields.io/badge/Platform-Colab%20%7C%20Jupyter-orange.svg)](https://colab.research.google.com/)

## 📌 Overview

This project collects recent user reviews from both **Google Play** and the **Apple App Store** for a Korean mobile financial app. It was developed to support product research, customer voice mining, and user experience optimization using real-world feedback.

The final output is a structured, multilingual Excel dataset (`all_reviews.xlsx`) ready for NLP, sentiment analysis, or UX research.

> ✅ Example app used: `증권금융 뱅킹 Plus`  
> Google Play ID: `co.kr.ksfc.mobile`  
> App Store ID: `1287896232` (KR store)

---

## 🎯 Project Objectives

- Automatically collect the **most recent user reviews** (up to 1,000 from Google Play, 500 from App Store)
- Normalize and merge multilingual feedback data
- Export a clean `.xlsx` dataset for downstream analysis
- Enable future extensions: sentiment analysis, trend detection, keyword clustering

---

## ⚙️ Tech Stack

| Component       | Description                         |
|----------------|-------------------------------------|
| `google-play-scraper` | Fetch reviews using Google Play API |
| `requests`      | Access Apple App Store RSS feed     |
| `pandas`        | Data wrangling and export           |
| `time`          | Rate-limiting for safe scraping     |
| `google.colab.files` | File download in Colab          |

---

## 🚀 How to Run

> ✅ Recommended: [Google Colab](https://colab.research.google.com/)

##1. Clone or open the repo in Colab:
```bash
!git clone https://github.com/AndrewLee-Korea/App-Review-Scraper.git  
```
##2.	Install required packages (if local):
pip install google-play-scraper pandas

##3.	Run the notebook App_Review_Scraper.ipynb
##4.	Output: all_reviews.xlsx will be created and downloaded automatically.
