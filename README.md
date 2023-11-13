# E-commerce_Web_Crawler - MOMO Shopping
This repo is for my course **Big Data Analysis** in NTUST.

## Overview

This project involves web scraping data from the MOMO website (https://www.momoshop.com.tw/main/Main.jsp) using Python. The script retrieves product information based on specified categories and keywords, and saves the data into Excel files. The code is designed to handle timeouts and provides a detailed report on URLs that experienced timeouts during the scraping process.

## Named Entity Recognition (NER)

Named Entity Recognition is a key feature of this project. It is used to extract important information from the scraped data, such as product titles, brands, links, prices, and more. The NER functionality is implemented in the get_product_information and get_product_extra_information functions.

## Project Structure

- `main_script.py`: The main Python script containing the web scraping logic.
- `query.xlsx`: Excel file with search queries organized by product categories.
- `timeout/`: Directory containing Excel files with timeout information.


## Prerequisites

- Python 
- Required Python packages
```
pip install pandas
pip install bs4
pip install requests
pip install re
Pip istall os
pip install tqdm
pip install fake_useragent
```
