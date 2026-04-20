# Amazon Price Tracker

## Overview
This project is a simple Python-based automation tool that tracks product prices from Amazon and logs them over time.  
The goal is to build a small dataset that can be used for analyzing price trends.

## Features
- Extracts product title and price from Amazon
- Stores data in CSV format
- Logs date for time-based tracking
- Sends email alerts when price drops below a threshold

## Tech Stack
- Python
- BeautifulSoup
- Requests
- CSV
- SMTP

## Implementation Details
The project leverages multiple Python libraries for data extraction, processing, and automation:
- `requests` for retrieving webpage content  
- `BeautifulSoup` for HTML parsing and data extraction  
- `csv` for persistent data storage  
- `datetime` for timestamping collected data  
- `smtplib` for email notification system

## Workflow
1. Send request to product URL
2. Parse HTML using BeautifulSoup
3. Extract title and price
4. Store data in CSV file
5. Trigger email alert if condition is met

## Sample Data
| Title | Price | Date |
|------|------|------|
| Travel Toiletry Organizer | 999 | 2026-04-20 |
| Travel Toiletry Organizer | 950 | 2026-04-21 |

## Project Structure
amazon-price-tracker/
│── AmazonScapper.py
│── AmazonScapper.csv
│── README.md

## Use Case
This project demonstrates how automated data collection can be used to build datasets for analysis and monitoring price changes over time.

## Future Scope
- Add price trend visualization
- Automate daily execution
- Track multiple products

## Author
Rupali Pasa


