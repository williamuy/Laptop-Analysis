# Best Buy Laptop Web Scrapper + Preprocessing and Visualization

## Description
This project focuses on scraping, cleaning, and visualizing laptop data from Best Buy. It aims to provide insights into laptop specifications, pricing, and trends through effective data manipulation and visualization techniques.

## Table of Contents
- [Web Scraping Process](#web-scraping-process)
- [Data Cleaning Methodology](#data-cleaning-methodology)
- [Data Visualization Overview](#data-visualization-overview)
- [Code Organization](#code-organization)
- [Findings](#findings)

## Web Scraping Process 
The data was scraped off Best Buy's laptop selection, as they provide comprehensive and up-to-date laptop listings. The web scrapping script utilizes Beautiful Soup and Selenium; extracting 30 variables from just under 1350 different laptops. 

To view the web scraper, you can find it in the [web scraping notebook](NoteBooks/Web_Scraper.ipynb).

To view the data, you can find it in the [data notebook](Data/laptops_(2).csv).


## Data Cleaning Methodology
The cleaning process involved removing irrelevant columns, handling missing values, standardizing datatypes, encoding and standarizing varaibles, and more. 

The cleaned dataset consists of 756 laptops from year 2018 to 2023, containing 13 variables.

To view the data preprocessing, you can find it in the [data cleaning notebook](NoteBooks/Data_Cleaning.ipynb).

To view the cleaned dataset, you can find it in the [data cleaning notebook](Data/CleanedLaptops.csv).

## Data Visualization Overview
A variety of visualizations were created, including histograms, scatter plots, and heatmaps, to explore different aspects of the data. These visualizations focus on price distribution, brand and operating system analysis, and uncovering potential correlations.

To view the full data visualization, you can find it in the [data viz notebook](NoteBooks/Data_Viz.ipynb).

## Code Organization
The repository is simply structured with the datasets in one folder, and the notebooks in another folder

## Findings

This analysis of laptop data from Best Buy has revealed some important insights into the laptop market over the years. 


1. **Correlation Among Features**:
   - The correlation heatmap indicated weak relationships among the laptop features, suggesting that no single feature dominates the pricing or customer satisfaction. This may be due to the lack of quality data from best buy. This insight guided the project's direction towards data visualization to narrate the story behind the numbers, rather than predictive modeling.

<div align="center">
  <img src="https://github.com/williamuy/Laptop-Analysis/assets/131928949/8edf513b-85e8-4e12-811b-a35b616ff98c)" alt="Correlation Heatmap" width="600"/>
</div>

2. **Price Distribution**:
   - The analysis of laptop prices showed a wide distribution, with a concentration in the $400 to $1200 range. This indicates a market targetted towards mid-range consumers, which makes sense as most consumers have budgets around this range.
     
<div align="center">
  <img src="https://github.com/williamuy/Laptop-Analysis/assets/131928949/a5bcd585-8a73-40c2-a0a3-c044dd7cca0e" alt="Price Distribution" width="600"/>
</div>

3. **Average Laptop Rating Trends**:
   - The trend of average laptop ratings over the years shows a significant rise in customer satisfaction post-2020. This may reflect improvements in laptop technology and cost-efficiency, enhancing the value for users.

<div align="center">
  <img src="https://github.com/williamuy/Laptop-Analysis/assets/131928949/011deb6b-b12d-4491-a689-90fa0ba6646d" alt="Average Laptop Rating Trends" width="600"/>
</div>

4. **Yearly Trends in Price and Quality**:
   - The dual-axis line chart tracking average price and average rating over time shows how price and ratings of laptops effect each other. As we can see, the move in parrell. When laptop prices go down, ratings also go down which suggests that consumers are willing to pay more for a better laptop. 

<div align="center">
  <img src="https://github.com/williamuy/Laptop-Analysis/assets/131928949/2abe3619-d6df-42fe-9572-6780a066776a" alt="Yearly Trends in Price and Quality" width="600"/>
</div>

5. **Brand Type Popularity**:
   - The breakdown of laptops by brand type (Mainstream, Gaming, Apple) highlighting the market share and popularity of each category. 
<div align="center">
  <img src="https://github.com/williamuy/Laptop-Analysis/assets/131928949/07c03a83-e717-4c68-b2f3-78da590a5c54" alt="Brand Type Popularity" width="600"/>
</div>

6. **Operating System Distribution**:
   - The pie chart of operating system distribution among laptops reveals that windows is still the dominant operating system in the laptop space. 
<div align="center">
  <img src="https://github.com/williamuy/Laptop-Analysis/assets/131928949/e9fe30b7-176b-4f59-ac84-7dd189599bd8" alt="Operating System Distribution" width="600"/>
</div>

<!--- 
7. **Brand and Operating System Interaction**:
   - The grouped bar chart showing the interaction between brands and operating systems provided insights into specific market niches. For instance, a high count of a particular brand-OS combination can reveal successful market strategies or strong brand loyalty.
<div align="center">
  <img src="https://github.com/williamuy/Laptop-Analysis/assets/131928949/74f9cb3f-8169-402a-ba95-43ad2235608d" alt="Brand and Operating System Interaction" width="600"/>
</div>
--->


