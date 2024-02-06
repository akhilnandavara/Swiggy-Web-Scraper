# Swiggy Bangalore City Restaurant Data Scraper

## Introduction
This repository contains a script written in Node.js using Puppeteer to scrape restaurant data from the Swiggy website for educational purposes only. The script gathers information about restaurants in Bangalore city and stores it in a MongoDB database.

## Disclaimer
This script is developed for educational purposes only. The use of this script to scrape data from Swiggy or any other website should comply with the website's terms of service and legal requirements. Scraping data from websites without permission may violate terms of service and could lead to legal consequences.

## Prerequisites
To run this script, you need to have the following installed:
- Node.js
- npm (Node Package Manager)
- MongoDB
- Puppeteer

## Installation
1. Clone this repository to your local machine.
2. Install dependencies by running `npm install`.

## Usage
1. Set up a MongoDB database and obtain the connection URL.
2. Create a `.env` file in the root directory of the project and add the following environment variables:
   ```
   MONGODB_URL=<your_mongodb_connection_url>
   ```
3. Run the script using the command `node scraper.js`.

## Functionality
The script performs the following tasks:

1. Launches a headless browser using Puppeteer.
2. Navigates to the Swiggy Bangalore city page.
3. Scrapes the URLs of restaurants listed on the page.
4. Scrapes data for each restaurant, including name, cuisine, and menu items.
5. Stores the scraped data into a MongoDB database.

## License
This project is licensed under the [MIT License](LICENSE).

## Note
This script has been created solely for educational purposes to demonstrate web scraping techniques using Puppeteer and data storage using MongoDB. It is not intended for commercial use or any purpose that violates Swiggy's terms of service or applicable laws. Use this script responsibly and ethically.