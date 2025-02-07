# mars-weather-challenge

This assignment involved web scraping and data analysis techniques to gather and analyze information related to Mars. The project was divided into two main parts: scraping Mars news articles and analyzing Mars weather data.

Part 1: Scrape Titles and Preview Text from Mars News 
In this section, automated browsing was utilized with Splinter to visit the Mars news site. The HTML content of the webpage was extracted using Beautiful Soup. The primary goal was to scrape and extract the titles and preview text of news articles. The gathered data was then stored in a structured Python data format, specifically a list of dictionaries, ensuring organization and ease of access.

Part 2: Scrape and Analyze Mars Weather Data 
For this section, the HTML table containing Mars weather data was extracted and converted into a Pandas DataFrame. Either Pandas or a combination of Splinter and Beautiful Soup was used to accomplish this task. The data was then structured with properly formatted column headings and appropriate data types.

Following the data extraction, an analysis was conducted to answer key questions:

The number of months present on Mars.

The total count of Martian days' worth of data.

Further analysis included data visualization to support findings on:

The month with the lowest and highest average temperature.

The month with the lowest and highest atmospheric pressure.

An estimation of the number of terrestrial days in a Martian year, with a visual approximation within 25% accuracy.

Finally, the processed DataFrame was exported into a CSV file to ensure data preservation and accessibility for further use.

