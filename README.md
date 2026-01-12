# NYC Airbnb Data Analysis

## Project Overview
I used this project to practice my data analysis skills on the New York City Airbnb dataset (2019). My goal was to take raw data, clean it up, and create visualizations to understand how prices vary across the city and what kind of listings are most popular.

I focused on grouping the data to see patterns in pricing and listing activity across the five boroughs.

## What I Did
1.  **Data Cleaning:** I checked the data for missing values and fixed logical issues (like filling in 0 for listings with no reviews).
2.  **Categorization:** I created a custom category for properties ("Low rented", "Average rented", "High rented") based on how many reviews they get per month. I used the quartiles (25%, 75%) to decide the cut-offs.
3.  **Visualization:** I created several plots to look at the data from different angles, including price distributions and host activity.

## Key Findings
* **Price Differences:** Manhattan is the most expensive borough, but there is a big range in prices. Queens is generally cheaper and has less price fluctuation.
* **Room Types:** Most of the listings are either "Entire home/apt" or "Private room". Shared rooms are very rare.
* **Rental Categories:** I found that "High Rented" properties (those with many reviews) don't always have the lowest prices.
* **Top Hosts:** There are some hosts who own a large number of properties, which suggests they are running a business rather than just renting out a spare room.

## Tools Used
* **Python**
* **Pandas** (for cleaning and grouping the data)
* **Seaborn & Matplotlib** (for creating the charts)
* **NumPy**

## Visualizations Included
* Bar chart of listings per neighbourhood group.
* Histogram of prices.
* Boxplot showing price ranges by property category.
* Grouped bar plot of average prices across boroughs.
* Bar chart of the top 10 hosts with the most listings.

## How to Run This
1.  Clone this repository.
2.  Make sure you have the libraries installed: `pip install pandas matplotlib seaborn numpy`
3.  Open the `main.ipynb` file in Jupyter Notebook to see the code and charts.
