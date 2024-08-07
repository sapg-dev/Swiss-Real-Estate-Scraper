The website has nothing to do with the backend of the scraper. It is for visualization only. Some pictures will not display as the images within the urls were not downloaded due storage concerns of downloading the pictures of every listing, instead the raw urls are used.




# Swiss Real Estate Web 

overlord.py is the file to run.

URL provided is simply for data visualization purposes, and not part of the scraper. It was made using react to display the data, and show that this data is usable and very valuable.

## Introduction
The Swiss Real Estate Web Scraper is a sophisticated Python-based tool designed for extracting detailed property information from various Swiss real estate websites, starting with immobilier.ch. This project is a testament to efficiency, accuracy, and scalability, making it a standout in the realm of web scraping.

## Key Features

### Dynamic Web Navigation
- Utilizes **Selenium WebDriver** for seamless interaction with web pages.
- Capable of handling dynamic content and AJAX-based websites.

### Detailed Data Extraction
- Extracts vital information such as prices, addresses, descriptions, and images.
- Transforms unstructured data into an organized format.

### Concurrent Scraping
- Employs **multithreading** to enhance efficiency by scraping multiple cantons simultaneously.
- Reduces overall scraping time without compromising system performance.

### Resilient Error Handling
- Robust error management mechanisms to ensure continuous operation.
- Gracefully recovers from common scraping interruptions.

### Efficient Data Storage
- Stores extracted data in structured **JSON files**, categorized by canton and type (buy/rent).
- Facilitates easy data retrieval and manipulation.

## Technical Overview

### Code Structure
- **Modular design**: Code is organized into distinct modules for scraping, parsing, and storing data.
- **Scalability**: Easily extendable to incorporate additional websites or functionalities.

### Efficiency and Threading
- **Thread-safe operations**: Ensures data integrity when scraping in parallel.
- **Optimized resource usage**: Balances the load between CPU and memory resources.

## Future Plans
- **Expansion to other platforms**: Plans to include other major real estate platforms like homegate.ch.
- **Free API**: Aiming to provide a free API for accessing scraped real estate data (details to be confirmed).

## Installation and Usage
- Requirements: Python 3.x, Selenium WebDriver.
- Installation instructions and usage details to be provided.

I don't welcome contributions, but you are welcome to freely fork the project and experiment with it. 

Web Sraping is legal.
