# Carousell Mobile Phone Transactions Analysis
![Carousell Logo](https://github.com/kevinmok2011/Python_Web_Scrapping_Repo/blob/main/carouselllogo.png)

## **Overview**

This project aims to analyze mobile phone transactions on the Carousell platform, focusing on brand popularity, pricing trends, and transaction status. The analysis provides insights into user behaviors, preferences, and market dynamics within the Carousell marketplace.

## **Introduction**

The objective of this project is to delve into the world of mobile phone transactions on Carousell, an online marketplace platform. The project aims to uncover insights into brand preferences, pricing dynamics, and transaction status distribution by employing web scraping techniques, data analysis, and visualization tools.

## **Methodology**

Data Collection and Transformation: HTML elements are extracted from Carousell listings using the 'BeautifulSoup' and 'requests_html' libraries. These elements are then transformed into structured data, including product name, price, description, and status (used/new).

Brand Identification: The 'brand_detection' mechanism accurately attributes each listing to a specific brand based on the product name.

Data Visualization: Visualizations include a stacked bar chart illustrating the total number of brands and the status distribution (used/new) for items listed on Carousell.

Price Analysis: Data is grouped by brands, and average and median prices are calculated using the 'statistics' library. A bar chart is generated to display these metrics for each brand.

## **Requirements**

1. Python

1. BeautifulSoup

1. requests_html

1. pandas

1. matplotlib

1. statistics

## **Results**

The stacked bar chart provides an overview of the brand distribution and status prevalence for Carousell mobile phone listings.
Bar charts display average and median prices for each brand, offering insights into pricing trends.
Conclusion

The project's insights enrich the understanding of Carousell's mobile phone market, highlighting brand popularity and pricing dynamics. This analysis serves as a valuable resource for sellers seeking strategic insights and buyers making informed decisions.

**Author**

Kevin Mok

Email: kevinmok2011@gmail.com
