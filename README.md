# BeautifulSoup4
![alt text](https://github.com/Zaheer-10/Code_Red/blob/main/Images/BS%24.jpg?raw=true)
BeautifulSoup is a Python library for pulling data out of HTML and XML files. It creates a parse tree for parsed pages that can be used to extract data from HTML, which is useful for web scraping.

This project is a Python script that uses BeautifulSoup4 to scrape and parse web pages. It can extract data from HTML and XML documents .So I have used IPL_Auction 2023 ,flipkart product page  and Bangalore Hotel Booking  to extract the tabel , reviews etc.

# Installation/Prerequisites
To run this project, you need to have Python 3 and BeautifulSoup4 installed on your system. You can install BeautifulSoup4 using pip:

`pip install beautifulsoup4`

You also need to have requests or urllib installed to fetch web pages. You can install requests using pip:

`pip install requests`

# References
The official documentation of BeautifulSoup4 can be found here:

https://www.crummy.com/software/BeautifulSoup/bs4/doc/

You can also refer to these tutorials and articles for more examples and explanations:

https://realpython.com/beautiful-soup-web-scraper-python/

https://www.dataquest.io/blog/web-scraping-tutorial-python/

https://www.edureka.co/blog/web-scraping-with-python/

# Examples
Here are some examples of how to use this script:

- To scrape the title and summary of the latest news articles from CNN, run:

`python scraper.py https://www.cnn.com/`

- To scrape the names and prices of the best-selling books from Amazon, run:

`python scraper.py https://www.amazon.com/best-sellers-books-Amazon/zgbs/books/`

- To scrape the lyrics of a song from Genius, run:

`python scraper.py https://genius.com/Lil-nas-x-montero-call-me-by-your-name-lyrics`

# FAQ
Some frequently asked questions about this project are:

- How do I specify a parser?
- You can pass the name of the parser as the second argument to the `BeautifulSoup` constructor. For example: `soup = BeautifulSoup(html, "lxml")`. If you don't specify a parser, BeautifulSoup will use the best one available on your system.
- How do I navigate the parse tree?
- You can use various methods and attributes to access different elements and attributes of the parse tree. For example: `soup.title` returns the <title> tag, `soup.find("p")` returns the first <p> tag, `soup.find_all("a")` returns a list of all <a> tags, etc. You can also use CSS selectors or regular expressions to find elements that match certain criteria.
- How do I modify the parse tree?
- You can use methods like `append`, `insert`, `replace_with`, `extract`, etc. to add, remove, or replace elements in the parse tree. You can also modify the attributes and contents of elements using assignment operators. For example: `link["href"] = "https://new.url"` changes the href attribute of a link element, `tag.string = "New text"` changes the text content of a tag element, etc.

- Q: How can I change the output format?
- A: You can modify the save_data function in the script to save the data in different formats, such as CSV, JSON, or SQL.

- Q: How can I handle errors and exceptions?
- A: You can use try-except blocks to catch and handle errors and exceptions that may occur while scraping or parsing web pages.

- Q: How can I scrape dynamic web pages that use JavaScript?
- A: You can use Selenium or other tools that can render JavaScript and interact with web elements.


# Link to My Blog: 
`https://soulofmercara10.medium.com/web-scraping-with-beautiful-soup-894f02e7d3d7`

