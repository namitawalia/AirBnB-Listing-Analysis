
# Project Overview

This project focuses on analyzing Airbnb listings in Paris. Using Python libraries such as **Pandas**, **Seaborn**, and **Matplotlib**, we explored and visualized key trends related to host behaviors, listing prices, and accommodations in various Paris neighborhoods over time. 

## Objectives

The main goal was to gain insights into:
- The distribution of listings across different neighborhoods in Paris.
- Pricing trends for various types of accommodations.
- The impact of new hosts and overall Airbnb growth over time.

## Data Exploration and Cleaning

- **Data Source**: The dataset includes 279,712 Airbnb listings, with 33 columns of attributes such as `host_id`, `listing_id`, `price`, `neighbourhood`, and `review_scores`.
- **Date Parsing**: We converted relevant date columns (e.g., `host_since`) into a proper datetime format to facilitate time-based analysis.
- **Handling Missing Values**: Some columns had missing data, such as `host_response_rate` and `host_acceptance_rate`. These were handled during data exploration.
- **Filtering**: We filtered the data to focus on listings based in **Paris**, specifically looking at key attributes like `host_since`, `neighbourhood`, `accommodates`, and `price`.

## Analysis Techniques

### Descriptive Statistics:
- Calculated descriptive statistics to examine key metrics like average prices, accommodation sizes, and host activity over time. For example, the average price per listing in Paris was approximately **113 Euros**, with a large variation across different neighborhoods.

### Data Aggregation:
- Grouped listings by neighborhoods and years to analyze price trends and new host activity. This helped identify neighborhoods with the highest and lowest average listing prices, as well as how the number of hosts evolved over time.

### Visualization:
- We created visualizations using **Seaborn** and **Matplotlib** to display:
    - Average listing prices across Parisian neighborhoods.
    - Pricing trends based on accommodation size.
    - The number of new Airbnb hosts by year.
    - Price changes over time.

### Key Insights:
- Certain upscale neighborhoods like **Elysee** and **Louvre** had the highest average prices, while **Menilmontant** and **Buttes-Chaumont** were more affordable.
- Regulatory changes around 2015 seemed to correlate with fewer new hosts but rising prices across the city.

## Outcome

This project provided a comprehensive overview of Airbnb listings in Paris, uncovering pricing patterns and host trends. By examining the impact of local regulations and other market forces, these findings can help both hosts and potential guests better understand the dynamics of the Paris Airbnb market.
