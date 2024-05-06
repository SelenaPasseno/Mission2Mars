# Mission2Mars
Instructions
Part 1: Scrape Titles and Preview Text from Mars News
Create a Beautiful Soup object and use it to extract text elements from the website.
Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:
Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview. An example is the following:
Store all the dictionaries in a Python list.
Print the list in your notebook.


Part 2: Scrape and Analyze Mars Weather Data
Open the Jupyter Notebook in the starter code folder named part_2_mars_weather.ipynb. You will work in this code as you follow the steps below to scrape and analyze Mars weather data.
Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape. Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.
Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. Here’s an explanation of the column headings:

id: the identification number of a single transmission from the Curiosity roverterrestrial_date: the date on Earth
sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
ls: the solar longitude
month: the Martian month
min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
pressure: The atmospheric pressure at Curiosity's location
Convert the data to the appropriate datetime, int, or float data types.

HINT
Analyze your dataset by using Pandas functions to answer the following questions:
How many months exist on Mars? 12
How many Martian (and not Earth) days worth of data exist in the scraped dataset? 1867
What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
Find the average minimum daily temperature for all of the months.
Plot the results as a bar chart.
Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
Find the average daily atmospheric pressure of all the months.
Plot the results as a bar chart.
About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
Consider how many days elapse on Earth in the time that Mars circles the Sun once.
Visually estimate the result by plotting the daily minimum temperature.
Export the DataFrame to a CSV file.

Requirements
Part 1: Scrape Titles and Preview Text from Mars News (40 points)
Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup). (10 points)
The titles and preview text of the news articles were scraped and extracted. (20 points)
The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries. (10 points)
Part 2: Scrape and Analyze Mars Weather Data (60 points)
The HTML table was extracted into a Pandas DataFrame. Either Pandas or Splinter and Beautiful Soup were used to scrape the data. The columns have the correct headings and data types. (15 points)
The data was analyzed to answer the following questions: (10 points)
How many months exist on Mars? (5 points) 12
How many Martian days' worth of data are there? (5 points) 1867
The data was analyzed to answer the following questions, and a data visualization was created to support each answer: (30 points)
Which month, on average, has the lowest temperature? The highest? (10 points) Lowest/Highest: Month 3. Month 8.
Which month, on average, has the lowest atmospheric pressure? The highest? (10 points) Low/High  Month 6, Month 9
How many terrestrial days exist in a Martian year? A visual estimate within 25% was made. (10 points)- Aproximately 700 days
The DataFrame was exported into a CSV file. (5 points) Done.
