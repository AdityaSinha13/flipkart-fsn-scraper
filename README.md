# 🛍️ Flipkart FSN Scraper

A Python-based Flipkart scraper that automates the extraction of product information using Flipkart FSNs (Flipkart Serial Numbers).

The notebook reads a list of FSNs from a CSV file, visits the corresponding Flipkart product pages, extracts key product details, and exports the results into an Excel file. This tool is useful for product research, catalog management, competitor analysis, and e-commerce data collection.

---

## ✨ Features

* 📥 Read Flipkart FSNs from a CSV file
* 🔍 Scrape product details directly from Flipkart
* 🏷️ Extract product title
* 💰 Extract selling price
* ⭐ Extract product rating
* 📝 Extract review count
* 🏢 Extract seller information
* 🔗 Capture product URL
* 📤 Export results to an Excel file
* 📒 Simple Jupyter Notebook workflow

---

## 📂 Repository Structure

```text
flipkart-fsn-scraper/
│
├── Scrapper Tool.ipynb
├── FSN Input.csv
└── FSN Output.xlsx
```

---

## 📥 Input

Populate **FSN Input.csv** with the Flipkart FSNs you want to scrape.

Example:

| FSN           |
| ------------- |
| BULGXYZ123456 |
| LSTABC987654  |

---

## 📤 Output

After execution, the scraper generates **FSN Output.xlsx** containing information such as:

* FSN
* Product Title
* Product Price
* Product Rating
* Review Count
* Seller Name
* Product URL
* Scraping Status

---

## 🛠 Tech Stack

* Python
* Selenium
* Pandas
* Requests
* BeautifulSoup
* Jupyter Notebook

---

## 🚀 Getting Started

1. Clone this repository.

```bash
git clone https://github.com/AdityaSinha13/flipkart-fsn-scraper.git
```

2. Open **Scrapper Tool.ipynb** in Jupyter Notebook or Visual Studio Code.

3. Install the required Python libraries if they are not already installed.

4. Before running the notebook, **update the input and output file paths inside the notebook** according to your local system.

5. Add the required FSNs to **FSN Input.csv**.

6. Run all notebook cells.

7. Once the scraping is complete, review the generated **FSN Output.xlsx**.

---

## ⚙ Configuration

The notebook contains configurable file paths for:

* Input CSV (`FSN Input.csv`)
* Output Excel (`FSN Output.xlsx`)

Update these paths before running the scraper if your files are stored in a different directory.

---

## 💡 Use Cases

* Product Research
* Marketplace Catalog Management
* Competitor Analysis
* Product Listing Preparation
* E-commerce Automation
* Price Monitoring

---

## ⚠️ Disclaimer

This project is intended for educational and research purposes only.

Please comply with Flipkart's Terms of Service and avoid excessive or abusive scraping.

---

## 🚧 Future Enhancements

* Automatic file path detection
* Excel (.xlsx) input support
* Multi-threaded scraping
* Retry mechanism
* Streamlit web interface
* Logging and reporting
* Proxy support
* CAPTCHA handling

---

## 👨‍💻 Author

**Aditya Sinha**

If you found this project useful, consider giving it a ⭐ on GitHub!
