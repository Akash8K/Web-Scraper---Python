# Web Scraping for Book Data

This Python script employs `requests`, `BeautifulSoup`, and `pandas` to extract book details from an e-commerce website. Users can input the number of pages to scrape, and the script gathers information such as title, price, and star rating for each book. The collected data is then organized into a Pandas DataFrame.

## Usage

1. **Base URL Definition:** Set the base URL pattern (`base_url`) for the e-commerce store.

2. **Pages to Scrape:** Input the desired number of pages when prompted.

3. **Script Execution:** Run the script to retrieve book details from the specified pages.

4. **DataFrame Output:** The script generates a Pandas DataFrame displaying book titles, prices, and star ratings.

5. **CSV Download (Optional):** Confirm downloading the DataFrame as a CSV file named `book_data.csv`. If confirmed, the file is saved in the script's directory.

Customize the base URL and adapt the script for different web scraping projects as needed.
