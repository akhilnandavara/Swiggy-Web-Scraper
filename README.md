﻿
# Restaurant Data Scraper

This Node.js script is designed to scrape restaurant data from various sources, including Google Maps, Swiggy, Zomato, and MagicPin. The scraped data includes information such as restaurant name, ratings, reviews, offers, and menu items. The extracted data can be stored or updated in a MongoDB database for further analysis.

## Prerequisites

Before running the script, ensure you have the following installed:

- Node.js
- MongoDB (optional, required if you want to store data in a database)
- Puppeteer

## Getting Started

1. Clone the repository to your local machine:

```bash
git clone https://github.com/akhilnandavara/Food-Price-Comparsion.git
```

2. Navigate to the project directory:

```bash
cd restaurant-data-scraper
```

3. Install dependencies:

```bash
npm install
```

4. Set up environment variables:

Create a `.env` file in the project directory and add the necessary environment variables. Example:

```env
MONGODB_URI=your-mongodb-uri
```

## Usage

1. Customize the scraping logic in the `scraper.js` file to meet your requirements.

2. Run the scraper:

```bash
node scraper.js
```

3. The script will fetch data for common restaurants from various sources, process it, and store or update the information in MongoDB.

## Configuration

- Adjust the scraping logic in `scraper.js` based on the structure and behavior of the target websites.
- Configure MongoDB connection settings in `.env` if you plan to use MongoDB for storing data.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve the scraper or add new features.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
