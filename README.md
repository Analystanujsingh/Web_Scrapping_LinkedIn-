# LinkedIn Web Scraping Project

## Overview

This project automates the process of scraping job listings from LinkedIn using Selenium in Python. The extracted job details are stored in a Google Sheet in real-time.

## Prerequisites

Make sure you have the following installed:

- Python (version 3.6 or higher)
- ChromeDriver (matching your Chrome browser version)
- Required Python packages: Selenium, BeautifulSoup, pandas, gspread

``bash
pip install selenium pandas gspread``

## Project Structure
`linkedinwebscraping.ipynb`: Main script for web scraping.
`credentials.json`: Google API credentials file.

## Getting Started
`Clone the repository`: git clone https://github.com/Analystanujsingh/Web_Scrapping_LinkedIn-.git

## Run the script
`python linkedinwebscraping.ipynb`
The script will open a Chrome browser, navigate to LinkedIn job listings, and start scraping data. Data will be stored in real-time on the specified Google Sheet.

## Google API Setup
Create a project on the Google Cloud Console.
Enable the Google Sheets API and download the credentials file as `credentials.json`.
Share your Google Sheet with the email address found in `credentials.json`.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
Inspired by the need for automating job data collection on LinkedIn.
Thanks to the developers of Selenium, BeautifulSoup, and gspread.
Feel free to contribute and open issues if you encounter problems or have suggestions!
