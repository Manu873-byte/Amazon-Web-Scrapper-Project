# Amazon Web Scraping Project

## Project Overview

This project focuses on extracting product data from Amazon using web scraping techniques in Python. The collected data is stored in a CSV file, and an automated email alert system is implemented to notify when the product price drops below a specified threshold.

## Tools & Libraries Used

**Python:** Core programming language used.

**Libraries:**

**requests —** For sending HTTP requests to fetch web pages.     
**BeautifulSoup —** For parsing HTML content and extracting data.     
**pandas —** For creating and managing CSV files.   
**smtplib —** For sending email notifications.   

## Workflow

**1. Fetching Product Data:**

Send a GET request to the Amazon product page URL.  
Parse the HTML content using BeautifulSoup.  
Extract key details like product title, price, and rating.  

**2. Storing Data in CSV:**

Structure the extracted data into a DataFrame.  
Export the DataFrame to a CSV file for record-keeping and analysis.  

**3. Price Drop Notification:**

Define a target price threshold.  
Compare the current product price with the threshold.  
If the price drops below the threshold, send an automated email alert.  

## Future Enhancements

Schedule automated runs using a task scheduler or cron job.  
Scrape multiple products and track price trends over time.  
Implement error handling for unavailable pages or incorrect data extraction.  



```python

```
