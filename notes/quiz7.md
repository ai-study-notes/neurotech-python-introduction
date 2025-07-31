# Quiz 7
**Which of the following is the correct syntax to extract all `href` links from a webpage using BeautifulSoup?**
```
a) soup.find_all('a')  ✓
b) soup.find_all('href')  ✗
c) soup.extract('a')  ✗
d) soup.get('href')  ✗
```
---
**What is the purpose of the `requests` library in web scraping?**
```
a) to retrieve web pages  ✓
b) to parse HTML  ✗
c) to analyze data  ✗
d) to manipulate images  ✗
```
---
**What is the purpose of using headers in a request?**
```
a) avoid detection  ✓
b) speed up scraping  ✗
c) modify HTML  ✗
d) access cookies  ✗
```
---
**What is the use of lxml or html.parse in BeautifulSoup?**
```
a) parse xml/html  ✓
b) send HTTP requests  ✗
c) download files  ✗
d) handle JSON  ✗
```
---
**What does the following code do?**
```py
import requests
from bs4 import Beatifusoup
response = request.get('https:/example.com')
soup = Beautifusoup(response.text;html.parser')
print(soup.title.text)
```
```
a) it prints the URL of the page  ✗
b) it prints the first heading of the page  ✗
c) it prints the HTML of the page  ✗
d) it prints the title of the webpage  ✓
```
---
**Which HTTP status code indicates a successful request?**
```
a) 404  ✗
b) 200  ✓
c) 403  ✗
d) 500  ✗
```
---
**Which library is commonly used for web scraping in Python?**
```
a) Pandas  ✗
b) Numpy  ✗
c) Matplotlib  ✗
d) BeautifulSoup  ✓
```
---
**What method in the `requests` library is used to send a GET request to a URL?**
```
a) request.post()  ✗
b) request.get()  ✓
c) request.open()  ✗
d) request.fetch()  ✗
```
---
###### last update: 28-7-2025