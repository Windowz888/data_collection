# data_collection
This module of web scraping and data analysis, with a focus on acquiring and processing Mars-related material. This project's key tools include Splinter for automatic browsing, Beautiful Soup for HTML parsing, and Pandas for data analysis, all of which work together to yield significant insights on the weather on Mars.


The project's deliverables are grouped into two categories. The first deliverable is scraping the titles and preview text of Mars news stories, while the second entails scraping and evaluating Mars meteorological data.

The project files can be obtained on GitHub in the Module 11 Challenge files directory.

The first stage of the project, as documented in the Jupyter Notebook part_1_mars_news.ipynb, involves visiting the Mars news site utilizing automated browsing. The following step is to extract the text elements from the website using Beautiful Soup. The retrieved news article names and preview text are then stored in Python data structures for simple editing and access. This scraped data can also be exported to a JSON file for easy distribution if needed.

The second portion of the project, described in part_2_mars_weather.ipynb, starts with an automated search of the Mars Temperature Data Site. The data in the HTML table on the site is then scraped using Beautiful Soup. This scraped data is compiled into a Pandas DataFrame, with column headers named appropriately. Each column's data types are then assessed and cast into the appropriate format as needed.

Following data gathering, an analysis is carried out to address key issues concerning Mars' weather. These topics concern the number of months on Mars, the number of Martian days of data in the dataset, the coldest and warmest months on Mars, and the months with the lowest and highest atmospheric pressure. These analyses are displayed using bar charts for ease of comprehension. In addition, the number of terrestrial (Earth) days in a Martian year is estimated.

Finally, the scraped and analyzed data is exported to a CSV file for further usage and sharing. This data's insights provide a view into Mars' weather patterns, particularly in terms of temperature and air pressure.
