# EquipNet-Ebay-Web-Scraper

A Python-based web scraping tool that automates the extraction of auction data from EquipNet, including lot details, titles, models, locations, and dates. It also fetches average listed and sold prices from eBay for comparison, saving the results to a CSV file for analysis. Built with Selenium, BeautifulSoup, and Pandas.

---

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Support](#support)

---

## Features
- **Automated Login**: Automatically logs into the EquipNet website using provided credentials or saved cookies.
- **Data Extraction**: Extracts detailed information about auction items, including lot numbers, titles, models, locations, start dates, and end dates.
- **eBay Price Comparison**: Fetches average listed and sold prices from eBay for the extracted items.
- **CSV Export**: Saves the extracted data along with eBay price comparisons into a CSV file for further analysis.

---

## Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/EquipNet-Ebay-Web-Scraper.git
   cd EquipNet-Ebay-Web-Scraper

    Install Dependencies:
    Ensure you have Python 3.8+ installed. Then, install the required packages using pip:
    bash
    Copy

    pip install -r requirements.txt

    Set Up ChromeDriver:

        Download the appropriate version of ChromeDriver for your Chrome browser from here.

        Ensure the ChromeDriver executable is in your system's PATH or specify its location in the script.

Usage

    Run the Script:
    bash
    Copy

    python main.ipynb

    Input Credentials:

        The script will prompt you to input your EquipNet and eBay credentials if not already hardcoded.

    Output:

        The script will generate a CSV file named product_data.csv containing the extracted data and eBay price comparisons.

Configuration

    EquipNet Credentials: Update the Username and Password fields in the script with your EquipNet login credentials.

    eBay Credentials: Update the email_field and password_field sections in the script with your eBay login credentials.

Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.
License

This project is licensed under the MIT License. See the LICENSE file for details.
Acknowledgments

    Selenium for browser automation.

    BeautifulSoup for HTML parsing.

    Pandas for data manipulation and CSV export.

Support

If you encounter any issues or have questions, please open an issue on the GitHub repository.
Copy


### Notes:
- Replace `your-username` with your actual GitHub username in the repository URL.
- Ensure the `LICENSE` file is added to the repository if you choose to use the MIT License or any other license.
- This template is structured for clarity and ease of navigation, making it user-friendly for contributors and users.
