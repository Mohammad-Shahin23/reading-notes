# Class Reading 17

## What are the key differences between scraping static and dynamic websites?


- Static websites: These websites are built with HTML and CSS and typically serve the same content to all users. 
Scraping static websites involves parsing the HTML structure to extract desired data, which is relatively straightforward.
- Dynamic websites: These websites use client-side technologies like JavaScript to generate content dynamically. 
Data may be loaded asynchronously or fetched from APIs. 
Scraping dynamic websites requires executing JavaScript, interacting with the page, and capturing the rendered content. 
This can be more complex and may require the use of specialized tools or frameworks.
## Explain at least three techniques or best practices that can be employed to avoid getting blocked while scraping websites.
- Respect robots.txt: Check the website's robots.txt file to understand any restrictions or guidelines provided by the website owner regarding scraping. Adhering to these guidelines helps maintain a positive scraping experience.
- Use request headers and user agents: Set appropriate request headers and user agent strings to mimic the behavior of a web browser. This helps avoid detection as a bot and improves the chances of successful scraping.
- Implement rate limiting and delays: Control the rate of requests to the website by introducing delays between requests. Mimic human browsing behavior by adding random intervals between requests to avoid triggering rate limits or detection algorithms.

## What is Playwright, and how does it assist in web scraping tasks? Provide an example of a use case where Playwright would be particularly beneficial.
- Playwright is an open-source browser automation tool that enables scraping and interaction with web pages using various programming languages.
- It provides a high-level API to automate web browsers (Chrome, Firefox, etc.) and performs tasks like filling forms, clicking buttons, and extracting data.
- Playwright is particularly beneficial for web scraping when websites heavily rely on JavaScript, dynamic content, or single-page applications (SPAs). 
It can handle these scenarios by executing JavaScript on the page, capturing AJAX requests, and providing access to the rendered content
## Describe the purpose of using Xpath in web scraping, and provide an example of an Xpath expression to select a specific HTML element from a webpage.
- Xpath is a language used to navigate and select elements in an XML or HTML document.
- It allows precise targeting of specific elements, attributes, or text within the document structure, making it useful for web scraping.