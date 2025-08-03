# 🏠 Zameen.com Web Scraper - Bahria Town, Islamabad

This Python script scrapes real estate listings from [Zameen.com](https://www.zameen.com), specifically targeting Bahria Town, Islamabad. The collected data includes prices, locations, bedroom and bathroom counts, area, and more. It scrapes multiple pages automatically and exports the data into a structured CSV file.

---

## 📌 Features

- Automatically navigates through multiple pages of listings.
- Extracts key property details:
  - Price
  - Address/Location
  - Bedrooms
  - Bathrooms
  - Area
  - Heading/Title
  - Time Added
- Saves data into a `zameen_bahria_town.csv` file.
- Uses `requests`, `BeautifulSoup`, and `pandas`.

---

## 🧠 Use Cases

- Data for real estate price analysis.
- Feature extraction for ML models.
- Practice project for web scraping.
- Data visualization and market insights.

---
## 🚀 How to Run

```bash
git clone https://github.com/razaq090/realestate-data-scraper-from-zameen.com-website.git
cd realestate-data-scraper-from-zameen.com-website
python zameen_scraper.py

---

## 🧾 Requirements

Install the required Python libraries:

```bash
pip install requests beautifulsoup4 pandas



