This project's focus is to help you extend skill acquired in class to scrape the local Jumia online shop using Python, Beutiful soup and requests (latter two are python libaries). You will be required to scrape links of products from the deals of the week in the homepage. After that, you'll create an algorithm to determine a products popularity and make recommendations to sellers about the type of products they ought to sell. For a similar but no so close scraping case, visit this site to learn more.

Standard Programming Procedures.
For this case, the following deliverables should be achieved at bare minimum.

Set up your python environment to have bs4 and requests libraries if not exists. Optionally, you might need pandas for data displaying but I'll recommend using csv library for this.
Recall on regular expression and make neccessry imports.
Using requests, check whether the link to the jumia site can be scrapped. Remember the status code and what each means.
Explore the page structure with chrome devtools to understand the product division you want to scrape.
From there, you'll be tasked to collect the following information: (Note: products scrapped should be from the deals of the week section in the homepage)
i) Product Name
ii) Brand Name
iii) Price (Ksh)
iv) Discount if Available (%)
v) Total Number of Reviews
vi) Product Rating (out of 5). 
