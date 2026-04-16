# EXP_17
Web Scraping and Data Extraction using Python
This repository contains the implementation of Experiment 17, focusing on automated data extraction from web pages using Python. The project demonstrates how to fetch HTML content and parse specific data points using industry-standard libraries.

👤 Student Information
Name: Shreyas Wani

PRN: 25070123131

Institute: Symbiosis Institute of Technology (SIT), Pune

🎯 Aim
To implement web scraping techniques in Python to extract structured information from websites for data analysis and processing.

🛠️ Technologies Used
Language: Python

Libraries: * Requests: To send HTTP requests and retrieve page content.

BeautifulSoup4 (bs4): To parse HTML and extract specific tags/attributes.

Environment: Google Colab / Jupyter Notebook

📑 Key Features Implemented
1. HTTP Request Handling
Using the requests library to connect to a target URL and retrieve the raw HTML source code. It includes handling status codes to ensure the connection is successful.

2. HTML Parsing
Utilizing BeautifulSoup to navigate the HTML DOM tree.

Tag Extraction: Finding specific elements like <h1>, <p>, and <a>.

Attribute Retrieval: Extracting links (href) and class-based content.

3. Data Structuring
The script processes unstructured web data into a readable format, which is the foundational step for building datasets for machine learning or research.

🚀 How to Run
Clone the repository:

Bash
git clone https://github.com/your-username/web-scraping-python.git
Install the required dependencies:

Bash
pip install requests beautifulsoup4
Execution:
Open the .ipynb file in Google Colab or Jupyter and run the cells. Ensure you have an active internet connection to allow the requests library to fetch the live web pages.
