# Amazon Price Tracker

## Overview
This project is a Python-based automation tool that tracks product prices from Amazon and logs them over time.  
It builds a simple dataset that can be used for monitoring and analyzing price trends.

---

## Features
- Extracts product title and price from Amazon  
- Stores data in CSV format  
- Logs date for time-based tracking  
- Sends email alerts when price drops below a threshold  

---

## Tech Stack
- Python  
- BeautifulSoup  
- Requests  
- CSV  
- SMTP  

---

## Implementation Details
The project uses multiple Python libraries to handle data extraction and automation:

- `requests` for fetching webpage content  
- `BeautifulSoup` for parsing HTML and extracting data  
- `csv` for storing structured data  
- `datetime` for recording timestamps  
- `smtplib` for sending email notifications  

---

## Project Workflow
1. Send HTTP request to the product URL  
2. Parse HTML content using BeautifulSoup  
3. Extract product title and price  
4. Store data in CSV file  
5. Check price condition and trigger email alert  

---

## Sample Data

| Title | Price | Date |
|------|------|------|
| Travel Toiletry Organizer | 999 | 2026-04-20 |
| Travel Toiletry Organizer | 950 | 2026-04-21 |
| Travel Toiletry Organizer | 920 | 2026-04-22 |

---

## Data Analysis Potential
- Track price trends over time  
- Identify lowest price periods  
- Analyze discount patterns  
- Visualize price fluctuations  

---

## Project Structure
amazon-price-tracker/
│── amazon_scraper.py
│── AmazonScapper.csv
│── README.md

---

## Future Improvements
- Add price trend visualization  
- Automate daily execution  
- Track multiple products  
- Store data in database  

---

## Use Case
This project demonstrates how automated data collection can be used to build datasets for analysis and monitor product pricing over time.

---

## Author
Rupali Pasa
