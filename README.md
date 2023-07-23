# Web_Crawler
Web crawling is the process of indexing data on web pages by using a program or automated script. 
These automated scripts or programs are known by multiple names, including web crawler, spider, spider bot, and often shortened to crawler.

Web crawlers copy pages for processing by a search engine, which indexes the downloaded pages so that users can search more efficiently. 
The goal of a crawler is to learn what webpages are about. This enables users to retrieve any information on one or more pages when it’s needed.

Web Crawler is a bot that downloads the content from the internet and indexes it. 
The main purpose of this bot is to learn about the different web pages on the internet. 
This kind of bots is mostly operated by search engines. By applying the search algorithms to the data collected by the web crawlers, search engines can provide the relevant links as a response for the request requested by the user. 
In this article, let’s discuss how the web crawler is implemented. 

# Motivation for project 
Web crawler when done sequentially is very slow and requires a lot of bandwidth. 
Since we have learnt threads and multiprocessing we thought that implementing these techniques would help improve web crawling in the following ways: 
• Reduce the total time
• Increase the number of sites to crawl in a given amount of time
• Reduce the total bandwidth of the user

# Objective
To compare sequential web crawlers and web crawlers using threads to find out if using threads in web crawlers can help save time.
Our main objective is
• Show the implementation of Web Crawling
• To reduce the total time using threading in web crawlers
• To increase the number of sites that can be visited by the crawler in a given amount of time
