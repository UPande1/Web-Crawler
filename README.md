# Web-Crawler
A Web Crawler is a program that navigates the Web and finds new or updated pages for indexing. The Crawler starts with seed websites or a wide range of popular URLs (also known as the frontier) and searches in depth and width for hyperlinks to extract.

A Web Crawler must be kind and robust. Kindness for a Crawler means that it respects the rules set by the robots.txt and avoids visiting a website too often. Robustness refers to the ability to avoid spider traps and other malicious behavior. Other good attributes of a Web Crawler are distributivity amongst multiple distributed machines, expandability, continuity, and the ability to prioritize based on page quality.

Simple Java crawler to crawl web pages on the same domain. If your page is redirected to another domain, that page is not picked up EXCEPT if it is the first URL tested. You can do this:

Crawl from a start point, defining the depth of the crawl, and decide to crawl only a specific path
Output: 1) The Page Title
        2) The Page URLs
        3) The Page Text
        
I have connected the MySQL database to create a table for all the output.


Experimental support for verifying that assets on a page work
