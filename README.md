# webscraping-challenge
# Background
You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

Deliverable 1: Scrape titles and preview text from Mars news articles.
    1.Use automated browsing to visit the Mars news siteLinks to an external site.. Inspect the page to identify which elements to scrape.
    2.Create a Beautiful Soup object and use it to extract text elements from the website.
    3.Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:
    Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview. An example is the following:
    {'title': "NASA's MAVEN Observes Martian Light Show Caused by Major Solar Storm",
    'preview': "For the first time in its eight years orbiting Mars, NASA’s MAVEN mission witnessed two different types of ultraviolet aurorae simultaneously, the result of solar storms that began on Aug. 27."}
    Store all the dictionaries in a Python list.
    Print the list in your notebook.
    4.Optionally, store the scraped data in a file (to ease sharing the data with others). To do so, export the scraped data to a JSON file. (Note: there will be no extra points for completing this.)
  
  Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.
    Open the Jupyter Notebook in the starter code folder named part_2_mars_weather.ipynb. You will work in this code as you follow the steps below to scrape and analyze Mars weather data.
    1.Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape. Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.
    2.Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.
    3.Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. Here’s an explanation of the column headings:
    id: the identification number of a single transmission from the Curiosity rover
    terrestrial_date: the date on Earth
    sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
    ls: the solar longitude
    month: the Martian month
    min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
    pressure: The atmospheric pressure at Curiosity's location
    4.Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.


# Analyze the Data
Step 5: Analyze the Data
Analyze your dataset by using Pandas functions to answer the following questions:

How many months exist on Mars?
How many Martian (and not Earth) days worth of data exist in the scraped dataset?
What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
Find the average the minimum daily temperature for all of the months.
Plot the results as a bar chart.
Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
Find the average the daily atmospheric pressure of all the months.
Plot the results as a bar chart.
About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
Consider how many days elapse on Earth in the time that Mars circles the Sun once.
Visually estimate the result by plotting the daily minimum temperature.



# File Submission:
    This assignment includes the following attchments:
      An Images folder containing screenshots of output graphs
      An Output folder containing exported csv files
      IPYNB files for part1 and part2 assignments
      A License
      A readme file  


# Acknowledgements
    **Internet Search: I utilized Google Search and slack overflow to research coding concepts, algorithms, and best practices.
    **Gemini AI: I leveraged Gemini AI to generate code suggestions, debug errors, and provide explanations for complex code segments.
    **Support Staff: I recieved help from my instructor and class TA during office hours for help with debugging errors and further explanation for complex code segments.
    **Please note: While these tools were invaluable in my development process, the final code is the result of my analysis, testing, and refinement.