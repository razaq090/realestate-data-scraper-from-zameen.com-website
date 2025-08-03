#  Zameen.com Web Scraper - Bahria Town, Islamabad

This Python script scrapes real estate listings from [Zameen.com](https://www.zameen.com), specifically targeting Bahria Town, Islamabad. The collected data includes prices, locations, bedroom and bathroom counts, area, and more. It scrapes multiple pages automatically and exports the data into a structured CSV file.

---

##  Features

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

##  Use Cases

- Data for real estate price analysis.
- Feature extraction for ML models.
- Practice project for web scraping.
- Data visualization and market insights.

---


##  Requirements

Install the required Python libraries:

```bash
pip install requests beautifulsoup4 pandas openpyxl
```

## How to Run
Clone this repository:

```bash

git clone git clone https://github.com/razaq090/realestate-data-scraper-from-zameen.com-website
cd zameen-web-scraper
```
## Run the script:

```bash
python zameen_scraper.py
```
The data will be saved as:
zameen_bahria_town.csv

## Project Structure

```graphql
zameen-web-scraper/
│
├── zameen_scraper.py           # Main scraper script
├── zameen_bahria_town.csv      # Output CSV file (auto-generated)
├── scraper_code.ipynb          # Notebook version (optional)
├── README.md                   # Project documentation
├── requirements.txt            # Python package dependencies
└── .gitignore                  # Files/folders to ignore
```

## Using This Data for ML or Graphs

- You can import the .csv into pandas for preprocessing.

- Use matplotlib, seaborn, or plotly to visualize property prices.

- Integrate with regression models to predict prices based on features.

## Disclaimer

This script is for educational and personal use only. Please respect the Zameen.com terms of service.

## License

Licensed under the MIT License. You're free to use, modify, and distribute this code.

##  Author

**Abdulrazaq**  
[My GitHub Profile](https://github.com/razaq090)  
[Email me](mailto:innovativerazaq.it@gmail.com)

Feel free to open issues or pull requests for suggestions or improvements.

```yaml
# Tip:
# Let me know if you want this automatically saved as a `.md` file on your system.

