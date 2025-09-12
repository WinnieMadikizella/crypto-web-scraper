# Automated Crypto Web Scraper – Python | Cryptocurrency | Data Automation

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python) 
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-Web%20Scraping-brightgreen) 
![Requests](https://img.shields.io/badge/Requests-HTTP-orange) 
![CSV](https://img.shields.io/badge/Data-CSV-lightgrey)  

## Executive Summary
This project is a **Python-based automated web scraper** that automates the collection of real-time Bitcoin prices from [CoinMarketCap](https://coinmarketcap.com/) and stores them in a CSV file with timestamps. It can be scheduled to run periodically, building a **historical dataset of crypto prices**. Eliminates manual tracking, builds historical datasets, and enables trend analysis.

**Impact**: Saves users hours of manual checking, creates reliable historical data, and enables informed decision-making for investors, analysts, and businesses.

**Next Steps**: Implement multi-crypto support, real-time alerts via email/WhatsApp, and visualization dashboards for trend insights.

---

## Business Problem
Cryptocurrency prices fluctuate rapidly, making it difficult for investors, analysts, and businesses to monitor them manually. Constantly refreshing pages is inefficient, error-prone, and time-consuming.

Solution:
- Automatically fetch the latest Bitcoin price
- Timestamp and store historical data
- Build datasets for analysis

Stakeholders: Crypto investors, financial analysts, price-conscious shoppers, and businesses monitoring competitor pricing.

## Real-World Relevance  

Think of it like **online shopping**:  
On Jumia or Amazon, you might wait for a phone, laptop, or TV price to drop. Instead of refreshing the page all day, you’d prefer an **automated system** to track the price for you and notify you when it changes.  

Cryptocurrency works the same way — prices change every second. Manually checking them is inefficient. This project solves that problem by:  
- Automatically fetching the latest Bitcoin price  
- Recording **when** the price was collected  
- Building a history of price changes over time  

**Use Cases:**  
- 🛒 Shoppers waiting for discounts  
- 📈 Investors tracking volatile markets  
- 📊 Analysts building trend models  
- 🏪 Businesses monitoring competitor prices  

---

## Methodology
1. **Data Scraping**: Python `requests` + `BeautifulSoup` to fetch Bitcoin prices.
2. **Automation**: Script runs periodically, appending results to CSV.
3. **Data Storage**: Structured CSV with timestamps for historical analysis.
4. **Scalability**: Modular code allows multi-crypto support and alert system integration.

Why These Tools: Python’s requests and BeautifulSoup provide reliable web scraping capabilities, while CSV offers a lightweight, accessible storage solution suitable for iterative analysis.

---

## Skills
- Python Programming: Loops, functions, error handling
- Web Scraping: requests, BeautifulSoup
- Data Handling: CSV manipulation, appending data, timestamps
- Automation: Scheduling periodic scripts
- Data Analysis Prep: Structured historical datasets for trend modeling.  

---

## Results & Recommendations

### Results:
- Successfully collected and timestamped Bitcoin prices in real-time
- Created historical datasets for analysis
- Removed manual tracking effort

### Lessons Learned:
- Handling website structure changes is crucial for scraper reliability
- Scheduling scripts ensures continuous data collection without manual intervention

### Recommendations:
- Stakeholders (investors/analysts) can leverage this historical data to identify patterns and make informed trading decisions
- Businesses can extend the scraper to track competitor cryptocurrency offerings or promotions
- Implement alert notifications to act on price thresholds proactively  

---

## Next Steps
- Add multi-cryptocurrency support to broaden applicability
- Build a real-time alert system via email or WhatsApp
- Create dashboards for visualizing price trends and volatility
- Address limitations such as potential website scraping blocks and API integration for more reliable data
- Explore integration with financial models for predictive analytics

## Installation & Usage  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/WinnieMadikizella/crypto-web-scraper.git
cd crypto-web-scraper
pip install requests beautifulsoup4 pandas
python crypto_scraper.py
```
The script will:
- Fetch the latest Bitcoin price
- Save it to crypto_prices.csv
- Append new entries with timestamps

![Sample CSV Output](actual_tracker_csv.png)
