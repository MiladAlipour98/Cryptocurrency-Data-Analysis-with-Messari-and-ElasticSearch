# Project Title: Cryptocurrency Data Analysis with Messari and ElasticSearch

## Overview
The objective of this project is to develop a program that retrieves, categorizes, and analyzes cryptocurrency data from the Messari website. The data will be stored in ElasticSearch and visualized using Kibana to support informed trading decisions. The project covers the retrieval, sorting, analysis, and graphical representation of data on various cryptocurrencies, enabling a better understanding of market trends.


## Steps

### Step 1: Crawl Cryptocurrency Data
1. **Source**: Retrieve data on 1,000 cryptocurrencies from [Messari](https://messari.io/) using a web scraping tool.
2. **Data Storage**: For each cryptocurrency, save data based on tags (such as market cap or category) in ElasticSearch for easy indexing and retrieval.


### Step 2: Sort Cryptocurrencies by Price (Descending Order)
- For each cryptocurrency tag, sort the cryptocurrencies by price in descending order.
  

### Step 3: Analyze Trends in the Last 30 Days
1. Retrieve cryptocurrencies within each tag and analyze if they’ve had a positive or negative trend over the past 30 days.
2. Calculate the percentage of cryptocurrencies with positive and negative trends in each tag.

### Step 4: Average Volume Analysis
1. Calculate the average trading volume for cryptocurrencies in each tag.
2. Sort cryptocurrencies within each tag based on whether their volume is above or below the average.

### Step 5: Visualize Data with Kibana
1. **Tool**: Install [Kibana](https://www.elastic.co/kibana), an Elastic visualization tool, to view the data stored in ElasticSearch.
2. **Setup**: Connect Kibana to the ElasticSearch instance.
3. **Visualizations**:
   - **Price Distribution**: Show a descending order of cryptocurrency prices in each tag.
   - **Trend Analysis**: Display percentages of positive and negative trends within each tag.
   - **Volume Analysis**: Graphically represent cryptocurrencies with volumes above and below the average.

   *Document the installation and setup process for Kibana and include screenshots or instructions on how to visualize data for each step.*

## Conclusion
This project offers a comprehensive approach to analyzing cryptocurrency data, covering data collection, sorting, trend and volume analysis, and visualization with Kibana. The results provide insights into price trends, trading volume, and market sentiment within different cryptocurrency tags. 
