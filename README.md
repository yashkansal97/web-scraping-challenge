# Web Scraping Challenge

## Goal

This challenge focused on web scraping using splinter and beautiful soup libraries of Python. It was further divided into two parts.

### Part 1

In this part, we focused on scarping a webpage with some article links, along with their previews. In the end, we created a list with all the article titles and the preview texts for these articles.

### Part 2

In this part, we focused on scraping a webpage with data from the Mars Curiosity Rover. We used splinter and beautiful soup to extract this data and save it in a dataframe.
Furthermore, we performed analysis on this dataframe and answered the following questions (refer to the notebook for the answers):
1. How many months exist on Mars?
2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
3. What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
    * Find the average the minimum daily temperature for all of the months.
    * Plot the results as a bar chart.
4. Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
    * Find the average the daily atmospheric pressure of all the months.
    * Plot the results as a bar chart.
5. About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
    * Consider how many days elapse on Earth in the time that Mars circles the Sun once.
    * Visually estimate the result by plotting the daily minimum temperature.
