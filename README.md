# LinkedIn Web Scraping Project

## Overview

This project aims to scrape job listings from LinkedIn using Selenium in Python. It automates the process of fetching job details and stores the data in a Google Sheet in real-time.

## Prerequisites

Make sure you have the following installed:

- Python (version 3.6 or higher)
- ChromeDriver (matching your Chrome browser version)
- Required Python packages: Selenium, BeautifulSoup, pandas, gspread

```bash
pip install selenium pandas gspread
Project Structure
linkedinwebscraping.ipynb: Main script for web scraping.
credentials.json: Google API credentials file. 
Getting Started
Clone the repository:
bash
Copy code
https://github.com/Analystanujsingh/Web_Scrapping_LinkedIn-.git
Install dependencies:
bash
Copy code

Run the script:

bash
Copy code
python linkedinwebscraping.ipynb
Usage
The script will open a Chrome browser, navigate to the LinkedIn job listings, and start scraping data.
Data will be stored in real-time on the specified Google Sheet.
Google API Setup
Create a project on the Google Cloud Console.
Enable the Google Sheets API and download the credentials file as credentials.json.
Share your Google Sheet with the email address found in credentials.json.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Inspired by the need for automating job data collection on LinkedIn.
Thanks to the developers of Selenium, BeautifulSoup, and gspread.
Feel free to contribute and open issues if you encounter problems or have suggestions!
