# Module_11_Challenge
This new assignment consists of two technical products.
# Code Source
Jupyter Notebook (part_1_mars_news.ipynb and part_2_mars_weather.ipynb)
# Part 1: Scrape Titles and Preview Text from Mars News
Opened jupyter notebook starter code to scrape Mars News website.  
1. Created a Beautiful Soup object and used it to extract text elements from the website.  
2. Extracted the titles and preview text of the news articles. Stored the scraping results in Python data structure as follows:  
- Stored each title-and-preview pair in a Python dictionary and, given each dictionary two keys: title and preview.  
- Stored all the dictionaries in a Python list.  
- Printed the list in jupyter notebook.  
3. Stored the scraped data in mars.json output file (JSON file).
# Part 2: Scrape and Analyze Mars Weather Data
Opened jupyter notebook starter code to scrape and analyze Mars weather data.
1. Created a Beautiful Soup object and used it to scrape the data in the HTML table.  
2. Assembled the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website.  
3. Examined the data types that are currently associated with each column. Converted the data to the appropriate datetime, int, and float data types.  
4. Analyzed dataset by using Pandas functions to answer the following questions within jupyter notebook (part_2_mars_weather.ipynb):  
- 12 months exist in Mars.  
- 1867 sols (Martian days) worth of data exist in the scraped dataset.  
- What are the coldest and warmest months on Mars (at the location of Curiosity):  
    - The average minimum daily temperature for all the months is the third month, and the eight month is the warmest.  
    - Plotted the results as bar charts within notebook.  
- Which months have the lowest and highest atmospheric pressure on Mars:  
    - Atmospheric pressure is, on average, lowest in th sixth month and highest in the ninth.  
    - Plotted the results as bar charts within notebook.  
- About how many terrestrial (Earth) days exist in a Martian year:  
    - Consider how many days elapse on Earth in the time that Mars circles the Sun once (answered within notebook).  
    - Plotted estimated result of the daily minimum temperature of each observation.  
5. Exported the DataFrame to a CSV file (mars_dat.csv)
# References:
The Mars News websiteLinks to an external site. is operated by edX Boot Camps LLC for educational purposes only. The news article titles, summaries, dates, and images were scraped from NASA's Mars NewsLinks to an external site. website in November 2022.  
Used google for pd.to_numeric, json.dumps(), and with open("filename", "mode") as file_variable, accessed March 2025.
