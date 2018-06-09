# WebScrapping

## What is Web Scraping? ##

Web scraping is a computer software technique of extracting information from websites. 
This technique mostly focuses on the transformation of unstructured data (HTML format) on the web into structured data (database or spreadsheet).

You can perform web scrapping in various ways, including use of Google Docs to almost every programming language. I would resort to Python because of its ease and rich ecosystem. 
It has a library known as ‘BeautifulSoup’ which assists this task. 

## Libraries required for web scraping ##

As we know, python is a open source programming language. You may find many libraries to perform one function. Hence, it is necessary to find the best to use library. I prefer BeautifulSoup (python library), since it is easy and intuitive to work on. Precisely, I’ll use two Python modules for scraping data:

    Urllib2: It is a Python module which can be used for fetching URLs. It defines functions and classes to help with URL actions (basic and digest authentication, redirections, cookies, etc). For more detail refer to the documentation page.
    BeautifulSoup: It is an incredible tool for pulling out information from a webpage. You can use it to extract tables, lists, paragraph and you can also put filters to extract information from web pages. In this article, we will use latest version BeautifulSoup 4. You can look at the installation instruction in its documentation page.

BeautifulSoup does not fetch the web page for us. That’s why, I use urllib2 in combination with the BeautifulSoup library.

Python has several other options for HTML scraping in addition to BeatifulSoup. Here are some others:

    mechanize
    scrapemark
    scrapy


## Transform anysite to json ##
