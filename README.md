# Yelp Data Collection Using API & Web Scraping

This repository contains two Jupyter Notebooks designed for collecting Yelp data using two different methods: Yelp API and Web Scraping. Whether you are interested in analyzing Yelp business reviews, understanding customer sentiments, or exploring dining options in a specific area, these notebooks provide a detailed step-by-step guide to gathering the data you need.

**NOTE:** I have removed the API Key from the notebook. <br>
You can get a Yelp API for free on the [Yelp Developer Website](https://docs.developer.yelp.com/).

## Notebooks Overview
**1. `Yelp_API.ipynb`**
This notebook demonstrates how to use the Yelp Fusion API to collect data about businesses listed on Yelp. It covers a simple framework for setting up your API key to make requests for specific data points such as business names, locations, reviews, etc.

**Features:**
- Setting up Yelp API credentials
- Making API requests to collect business information
- Filtering and sorting API responses
- Handling pagination to collect large datasets

**Requirements:**
- Yelp API Key
- Python packages: requests, json, pandas

**2. `Yelp_Web_Scraping.ipynb`**
This notebook offers a framework on how to scrape Yelp data directly from the website. It's particularly useful for data points that are not available through the API or for users who prefer not to use the API.

**Features:**
- Setting up a web scraping environment
- Navigating and parsing Yelp's website structure
- Extracting detailed business information, including reviews and user comments
- Efficiently managing request rates to avoid being blocked

**Requirements:**
- Python packages: requests, BeautifulSoup (from bs4), pandas

To install the packages:
``` bash
pip install requests pandas beautifulsoup4
```
