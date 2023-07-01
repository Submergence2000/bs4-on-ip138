# bs4-on-ip138
The web scraper for site.ip138.com is able to return all parsing results recorded on IP138 when a domain name is entered; when an IP address is input, it yields all the domain names that have been resolved from that IP on IP138.

### Principle:

The scraper operates on a principle that involves HTTP requests, parsing with Beautiful Soup, and regular expression matching.

### Usage Instructions:

```bash
pip install -r requirements.txt
```

After installation, you can directly call the function (or simply copy/paste it). I might package it after enhancing its functionalities, however, due to its current developmental stage, packaging plans are not yet definite.

### Future Enhancements:

In the future, I plan to include features like IP geo-location lookup, registration information query, subdomains, and Whois information search. However, I can't guarantee a timeline for these additions. The reason behind developing this project was due to the failure of the existing online codes that were supposed to fulfill these two functions, leading me to create and share my own scraper.

### Limitations:

Currently, the scraper does not simulate scrollable web pages, which means that the results provided are limited. But for typical domain names and IP addresses, this limitation does not pose a significant concern. I plan to implement the Selenium package for requests and simulate keyboard and mouse operations for future iterations.
