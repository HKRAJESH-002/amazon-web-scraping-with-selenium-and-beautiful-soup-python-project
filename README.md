🛒 Amazon Web Scraper using Selenium, BeautifulSoup, and Pandas
📌 Project Description
This project is a Python-based Amazon web scraper that extracts product information from Amazon search result pages using Selenium, BeautifulSoup, and Pandas. The scraper automates the process of browsing Amazon, parses product listings, and stores structured data for analysis or reporting purposes.

It's designed to gather details such as:

>Product Title

>Price

>Rating

>Number of Reviews

>Availability

>Product URL

📂 Technologies Used
>🕸️ Selenium: To handle dynamic content and interact with JavaScript-loaded web elements (like scrolling and clicking).

>🍲 BeautifulSoup: For parsing the HTML content returned by Selenium and extracting useful information.

>📊 Pandas: To clean, structure, and export the scraped data into .csv or .xlsx formats for further analysis.

🔧 Features
>Search Amazon with any keyword(s).

>Scrape multiple pages of search results.

>Handle dynamic content and popups.

>Export scraped data to CSV or Excel.

>Modular and scalable codebase.

>User-agent spoofing and delay simulation for minimal bot detection.

⚙️ How It Works
>Input Search Keyword: You provide the product or keyword you want to search.

>Selenium WebDriver: Launches a headless browser and performs the search.

>Pagination Loop: Iterates through a specified number of search result pages.

>HTML Parsing: Extracts product data using BeautifulSoup from each page.

>Data Storage: Cleans and stores the data using Pandas.

>Export: Saves the data in CSV/Excel format.
