# Challenge Objectives:
Deliverable 1: Scrape titles and preview text from Mars news articles. Optionally export the data into a JSON file or a MongoDB database.

Deliverable 2: Scrape and analyse Mars weather data, which exists in a table.

## Part 1:
Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup).
The titles and preview text of the news articles were scraped and extracted, and stored in a list of dictionaries.

## Part 2:
Splinter and Beautiful Soup were used to scrape the data.
The HTML table was extracted into a Pandas DataFrame. DataFrame was created with all columns listed on the website.

The dataset was analyzed using Pandas functions:to answer the following questions:

1. How many months exist on Mars? 12
2. How many Martian (and not Earth) days worth of data exist in the scraped dataset? 1867
3. What are the coldest and the warmest months on Mars (at the location of Curiosity)? Plot the average temperature by month. The coldest month in Curiosity's location is month 3. The hottest month in Curiosity's location is month 8.
4. Which months have the lowest and the highest atmospheric pressure on Mars? Plot the results as a bar chart. The month with the lowest atmospheric pressure is month 6. The month with the highest atmospheric pressure is month 9.
5. About how many terrestrial (Earth) days exist in a Martian year? Visually estimate the result by plotting the daily minimum temperature. There is roughly around 675 days in a Martian year from the plot.
