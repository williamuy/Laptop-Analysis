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
The data was sourced from Best Buy, chosen for its comprehensive and up-to-date laptop listings. Python scripts utilizing libraries such as Beautiful Soup and Selenium were employed for scraping, ensuring efficient and accurate data extraction.

To view the web scraper, you can find it in the [web scraping notebook](NoteBooks/Web_Scraper.ipynb).

## Data Cleaning Methodology
The cleaning process involved removing irrelevant columns, handling missing values, and standardizing data formats. Special attention was given to transforming categorical variables and normalizing numerical data for meaningful analysis.

To view the data preprocessing, you can find it in the [data cleaning notebook](NoteBooks/Data_Cleaning.ipynb).

## Data Visualization Overview
A variety of visualizations were created, including histograms, scatter plots, and heatmaps, to explore different aspects of the data. These visualizations focus on price distribution, brand and operating system analysis, and uncovering potential correlations.

To view the full data visualization, you can find it in the [data viz notebook](NoteBooks/Data_Viz.ipynb).

## Code Organization
The repository is simply structured with the datasets in one folder, and the notebooks in another folder

## Findings

This comprehensive analysis of laptop data from Best Buy has revealed several important insights into the laptop market. These findings are instrumental in understanding consumer preferences, market trends, and the evolving dynamics of laptop features. Here are the key findings:




1. **Correlation Among Features**:
   - The correlation heatmap revealed significant relationships between various laptop features. Notably, there might be a strong correlation between certain specifications (like processor speed, RAM) and price, indicating these features are key drivers in laptop pricing.

<div align="center">
  <img src="https://github.com/williamuy/Laptop-Analysis/assets/131928949/8edf513b-85e8-4e12-811b-a35b616ff98c)" alt="Correlation Heatmap" width="600"/>
</div>

2. **Price Distribution**:
   - The price distribution of laptops showcased a wide range, with a concentration in specific segments. This suggests a diverse market catering to different consumer needs, from budget-friendly to high-end laptops.
<div align="center">
  <img src="https://github.com/williamuy/Laptop-Analysis/assets/131928949/a5bcd585-8a73-40c2-a0a3-c044dd7cca0e" alt="Price Distribution" width="600"/>
</div>

3. **Average Laptop Rating Trends**:
   - The analysis of average laptop ratings by year provided insights into how customer satisfaction has evolved. A consistent trend (either upward or downward) over the years could indicate improvements in technology or changing consumer expectations.
<div align="center">
  <img src="https://github.com/williamuy/Laptop-Analysis/assets/131928949/011deb6b-b12d-4491-a689-90fa0ba6646d" alt="Average Laptop Rating Trends" width="600"/>
</div>


4. **Yearly Trends in Price and Quality**:
   - The dual-axis line chart tracking average price and average rating over time offered a nuanced view of the market. Notably, any parallel trends in pricing and ratings could suggest a correlation between perceived quality and cost.

<div align="center">
  <img src="https://github.com/williamuy/Laptop-Analysis/assets/131928949/2abe3619-d6df-42fe-9572-6780a066776a" alt="Yearly Trends in Price and Quality" width="600"/>
</div>

5. **Brand Type Popularity**:
   - The breakdown of laptops by brand type (Mainstream, Gaming, Apple) highlighted the market share and popularity of each category. The dominance of a particular type could reflect consumer preferences or market strategies by laptop manufacturers.
<div align="center">
  <img src="https://github.com/williamuy/Laptop-Analysis/assets/131928949/07c03a83-e717-4c68-b2f3-78da590a5c54" alt="Brand Type Popularity" width="600"/>
</div>

6. **Operating System Distribution**:
   - The pie chart of operating system distribution among laptops revealed the popularity of different operating systems (macOS, Windows, Chrome OS). This is indicative of consumer preferences and the competitive landscape among software giants.
<div align="center">
  <img src="https://github.com/williamuy/Laptop-Analysis/assets/131928949/e9fe30b7-176b-4f59-ac84-7dd189599bd8" alt="Operating System Distribution" width="600"/>
</div>

7. **Brand and Operating System Interaction**:
   - The grouped bar chart showing the interaction between brands and operating systems provided insights into specific market niches. For instance, a high count of a particular brand-OS combination can reveal successful market strategies or strong brand loyalty.
<div align="center">
  <img src="https://github.com/williamuy/Laptop-Analysis/assets/131928949/74f9cb3f-8169-402a-ba95-43ad2235608d" alt="Brand and Operating System Interaction" width="600"/>
</div>

These findings demonstrate an ability to extract meaningful insights from complex data sets. The analysis not only sheds light on current trends in the laptop market but also provides valuable information that can guide consumer choices and inform manufacturer strategies. By leveraging data scraping, cleaning, and visualization techniques, this project offers a comprehensive overview of the dynamic laptop market.

