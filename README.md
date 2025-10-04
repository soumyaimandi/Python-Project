🛒 Python Price Tracker with Web Scraping & Email Alerts


📌 Overview

This project is a Python-based price tracker that uses web scraping to monitor the price of any product (Amazon, Flipkart, etc.). If the product’s price drops below your set target, the script will automatically send you an email alert.

It is built entirely in Python, written and tested in Google Colab, and demonstrates:

Web scraping with BeautifulSoup

Sending requests with Requests

Automating email alerts with SMTP (Gmail)

Building a functional automation project for real-world use

🎯 Why is this useful?

Save money 💰 by tracking product price drops automatically

Learn web scraping in Python with real-world application

Practice Google Colab automation workflow

Understand secure Gmail app password usage for automation

⚙️ Features

✅ Scrapes product prices in real-time

✅ Works with Amazon / Flipkart (update selector class for other sites)

✅ Compares price against your target

✅ Sends instant email notifications on price drops

✅ Runs continuously with adjustable time intervals

🚀 Requirements
Environment

Python 3 (works on Google Colab)

Libraries

Make sure to import/install the following:
```python
pip install requests beautifulsoup4
```
Input Requirements

When running the script, you need to provide:

Product URL – The link of the product you want to track

Target Price – The price at which you want to be notified

Email Setup –

Your Gmail address

A 16-digit App Password (not your real password!)

Recipient email where the alert should be sent

⚠️ Important:

Enable 2-Step Verification on your Google account.

Generate an App Password at [![Google App Passwords](https://img.shields.io/badge/Google-App%20Passwords-blue?logo=google)](https://myaccount.google.com/apppasswords)

Use that 16-digit password in the script.

📧 Email Alert Example

When the price drops below your target, you’ll receive an email like this:
```python
Subject: Product Price Dropped!  

The price dropped to ₹49,999!  
This is below your target price of ₹50,000.  
Check the product here: https://www.amazon.in/example-product
```
🛠️ Technologies Used

Python 3

Google Colab

Requests

BeautifulSoup (bs4)

SMTP (smtplib)

📜 License

This project is for educational purposes. You can fork, modify, and use it for personal projects.
