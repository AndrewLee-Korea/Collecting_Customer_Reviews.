# 📱 App Review Scraper: Google Play & App Store

## 📌 Overview
This project implements a web scraper that collects user reviews from Google Play and Apple App Store. It enables data-driven sentiment and usability analysis for mobile applications using real-world user feedback.

Designed to support product improvement and user behavior research in the mobile financial app domain.

## 🎯 Purpose
As a digital strategy manager working on mobile banking platforms, I built this tool to analyze user sentiment and identify pain points across app versions and platforms. This project reflects my interest in data-driven product optimization and human-centered AI systems.

## ⚙️ Technologies Used
- **Language**: Python 3.9
- **Libraries**:
  - `google-play-scraper` (unofficial API)
  - `app-store-scraper` (via `app_store_scraper` or custom requests)
  - `pandas`, `json`, `matplotlib` for data handling and visualization
  - `Jupyter Notebook` for exploratory analysis

## 🧠 Features
- Retrieves user reviews based on:
  - App name or ID
  - Country and language
  - Rating score
  - Review date
- Saves structured data as `.csv` or `.json`
- Optional keyword filtering or sentiment tagging (NLTK or TextBlob)

## 🧪 Sample Output
| Username | Rating | Review Text | Date       | Platform  |
|----------|--------|-------------|------------|-----------|
| user123  | 2★     | 앱이 자주 멈춰요. 불편합니다. | 2024-08-14 | Google Play |
| mjkim    | 5★     | 깔끔한 디자인과 빠른 응답 좋아요. | 2024-09-01 | App Store   |
