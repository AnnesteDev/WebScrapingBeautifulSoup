#Web Scraping with Beautiful Soup
##A Tutorial from Real Python
[https://realpython.com/lessons/web-scraping-bs-overview/]()

API returns JSON - focused and specific info

Scraping returns HTML - needs parsing - if no API is available
1. Inspect - Go to link and use Developer Tools to find fields required for scraping
   1. Identify URL queries ([https://indeed.com/jobs?q=python&l=new+york]())
   2. Identify page structure(HTML/DOM)
2. Scrape
   1. Static websites - requests(`requests.get(url)`), re(`re.findall(r'python', str(response.content)`)
   2. Password - protected sites - requests can handle this
   3. Dynamic Sites - Selenium
3. Parse - make scraped html data readable - iterative process
   1. Find Elements by ID
   2. Find Elements by HTML Class Name
   3. Extract Text from HTML Elements
   4. Extract Attributes from HTML Elements

###ToDo:
1. `pip install requests`
2. `pip install bs4`

###Where to go from here:
1. Real Python course on the requests module
2. Scraping Dynamic Websites
   1. requests-html
   2. selenium
