# Airbnb Listing Analysis in Paris

## Project Overview
This project involves analyzing Airbnb listings in Paris to uncover insights about pricing trends, host activity, and neighborhood dynamics. The primary focus is to understand how factors such as the number of accommodations and location impact the price per night.

## Objectives
- Filter and analyze Airbnb listings in Paris.
- Investigate the relationship between the neighborhood and average price.
- Track new hosts over time and how prices have changed.
- Identify insights that can help stakeholders make informed decisions.

## Methodology

### Data Importing and Cleaning
- Imported the dataset using Pandas.
- Handled missing values and converted date columns to the appropriate format.

### Data Filtering
- Focused on listings located in Paris and retained relevant columns for analysis: `host_since`, `neighbourhood`, `city`, `accommodates`, and `price`.

### Data Exploration and Analysis Techniques
- Performed descriptive statistics to calculate the mean, min, max, and count of numeric fields.
- Grouped data by neighborhood to analyze average prices.
- Analyzed the relationship between accommodation capacity and pricing.

### Data Visualization
  - Used Seaborn and Matplotlib to visualize:
  - Average listing price by neighborhood.
  - Average price based on accommodation capacity.
  - Trends in new hosts and average prices over time.

## Insights
- Identified neighborhoods with varying average prices for listings.
- Noted a decrease in the number of new hosts and an increase in average prices following regulations introduced in 2015.

## Libraries Used
- **Pandas:** For data manipulation, cleaning, and aggregation.
- **NumPy:** For numerical operations and array handling.
- **Seaborn:** For data visualization (bar plots, trends).
- **Matplotlib:** For generating more complex visualizations (combined time series plot).
