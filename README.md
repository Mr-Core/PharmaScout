# PharmaScout

A simple Python-based price tracker bot built for personal use. It monitors specific product pages across several pharmacy websites and logs the daily prices into a file for manual review. The goal is to track price changes, especially discounts, and eventually automate notifications when a price drops.

---

## Project Goals (MVP)

- [x] Scrape current price from a list of hardcoded product pages (starting with pharmacy.hr).
- [ ] Save prices with timestamp into a local file.
- [ ] Compare the new price with the previously stored price.
- [ ] Log price changes (increase/decrease/unchanged).

---

## Future Plans

- Add support for multiple websites.
- Automatically send email alerts on price drops.
- Save data to a local or cloud-based database.
- Improve scraper to automatically detect price on arbitrary pages (experimental).
- Add a minimal web UI/dashboard or a command-line interface.

---

## Motivation

This project is solving a real-life annoyance: having to manually check multiple websites for price changes on a specific skincare product. Instead of checking each page every day, this bot will do it for me and eventually notify me when a good deal pops up.

It’s also a learning playground — I’m building this to practice Python, web scraping, file handling, and eventually scheduling, databases, and more.

---

## Tech Stack

- Python 3
- requests
- BeautifulSoup (bs4)
- Possibly: Selenium, smtplib (for email), sqlite3 or pandas (for storage)

---

## Project Structure (planned)

```
pharmascout/
├── data/
│   └── prices.csv
├── src/
│   └── scraper.py
├── logs/
│   └── activity.log
├── README.md
└── requirements.txt
```

---

## Status

🚧 In early development — currently focused on building a working price scraper for one site.

---
