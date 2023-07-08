# TF-IDF-implimentation
This project is an implementation of a web scraping search engine using the TF-IDF (Term Frequency-Inverse Document Frequency) algorithm, powered by Flask framework. It allows you to scrape web pages, build an index of terms, and perform searches based on relevance.

Features
Web scraping: The application can scrape web pages using Python's requests and BeautifulSoup libraries to extract textual content for indexing.
Indexing: The extracted content is processed to build an inverted index using the TF-IDF algorithm, which helps determine the relevance of terms in documents.
Search: Users can perform searches by entering keywords or phrases, and the application returns a ranked list of matching documents based on their relevance score.
Flask web interface: The project provides a user-friendly web interface built with Flask, allowing users to interact with the search engine through their web browsers.
Requirements
To run this project, make sure you have the following dependencies installed:

Python 3.x
Flask (install using pip install flask)
Requests (install using pip install requests)
BeautifulSoup (install using pip install beautifulsoup4)
