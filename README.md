# Web Scraping - klikdokter.com
<p align="center">
  <img width="300" height="300" src="https://asset-cdn.medkomtek.com/revamp/static/images/logo/logo-512.png">
</p>
KlikDokter is a website from Indonesia that was founded in 2008 . This website contains articles and videos about health created by doctors. Klikdokter collaborates with KKI (Indonesian Medical Council), ILUNI FK (Indonesian Faculty of Medicine Alumni Association), [1] ILUNI FKG (Indonesian Faculty of Dentistry Alumni Association), IDI (Indonesian Doctors Association) and other medical organizations. Since 2016, KlikDokter is owned and operated by PT Medika Komunika Teknologi, which is a joint subsidiary of KMK Online (KMK) and Kalbe.

# What is Web Scraping?
Web scraping, web harvesting, or web data extraction is data scraping used for extracting data from websites. Web scraping a web page involves fetching it and extracting from it. Fetching is the downloading of a page (which a browser does when a user views a page). Therefore, web crawling is a main component of web scraping, to fetch pages for later processing. Once fetched, then extraction can take place. The content of a page may be parsed, searched, reformatted, its data copied into a spreadsheet or loaded into a database. Web scrapers typically take something out of a page, to make use of it for another purpose somewhere else. An example would be to find and copy names and telephone numbers, or companies and their URLs, or e-mail addresses to a list (contact scraping).

# Web Scraping Techniques
In general, there are two ways you can do this:
- Manual: a method where you copy data by copy-pasting from a website
- Automatic: a method that uses code, an application, or a browser extension.

Web scraping is now made easier with the help of browser extensions and applications. There are six commonly used web scraping techniques, namely:
1. Copying data manually
2. Using regular expressions
3. HTML parse
4. Analyze DOM
5. Using XPath
6. Using Google Sheets

# Benefits and Problems of Web Scraping
Following are the four main advantages:
1. Getting Leads
2. Comparing Massive Data
3. Optimization of Reviews, Product Pricing and Service
4. Looking for Company Information

Although web scraping is a very helpful technique in extracting site data, there are also problems to its implementation. At least, the following five things you need to remember if you want to do it:
1. No web scraping technique is 100% effective
1. The data obtained is not always neat
1. Understanding of the structure of the website page remains an obligation
1. Your access to a website may be blocked
1. Not all websites are easy to extract data

# About The Project
The main goal of this project is to collect data on medicine names and descriptions from the klikdokter.com website, then extract them into a dataset and export them as excel and CSV files.

# Built with
- [**pandas**](https://pandas.pydata.org/)
- [**NumPy**](https://numpy.org/)
- [**lxml**](https://lxml.de/)
- [**Request**](https://docs.python-requests.org/en/latest/)
- [**Beautiful Soup**](https://beautiful-soup-4.readthedocs.io/en/latest/)

# Getting Started
Beautiful Soup is a Python library for pulling data out of HTML and XML files. It works with your favorite parser to provide idiomatic ways of navigating, searching, and modifying the parse tree. It commonly saves programmers hours or days of work. While the Requests allows you to send HTTP/1.1 requests extremely easily. There’s no need to manually add query strings to your URLs, or to form-encode your POST data. Keep-alive and HTTP connection pooling are 100% automatic, thanks to urllib3.

Read more for [**Beautiful Soup documentation**](https://beautiful-soup-4.readthedocs.io/en/latest/) and [**Request documentation**](https://docs.python-requests.org/en/latest/)
### **Prerequisites**
Here is how to run the library used in this project. First Install the list of libraries below on your device or kernel:
- Beautiful Soup <br>
  ```
  pip install beautifulsoup4
  ```
- Request <br>
  ```
  pip install requests
  ```
