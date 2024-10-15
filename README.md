# Property Price Analysis in Bandung

This project explores and analyzes property prices in various districts of Bandung, Indonesia. The dataset (from [this Kaggle Dataset](https://www.kaggle.com/datasets/khaleeel347/harga-rumah-seluruh-kecamatan-di-kota-bandung)) includes key features such as land area, building area, loan scheme, districts and house prices. The analysis aims to understand the relationships between these features and visualize trends in property prices across different districts.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Geospatial Analysis](#geospatial-analysis)
- [Technologies Used](#technologies-used)
- [Acknowledgments](#acknowledgments)

## Project Overview

This project examines house listings from a property dataset of Bandung. Through exploratory data analysis, it identifies key factors influencing property prices, including the size of land, number of rooms, and district location. Additionally, the project employs geospatial analysis to visualize district-level price patterns using open-source geographic data.

## Data Cleaning

Data cleaning involves removing missing values, handling outliers, and transforming columns to prepare the data for analysis. While initial cleaning is performed, additional steps are taken throughout the analysis to address specific issues such as outliers and logical inconsistencies.

## Exploratory Data Analysis

The exploratory analysis focuses on:
- Correlation between features (e.g., land area, number of rooms, carports) and their impact on house prices.
- Visualizing the distribution of house prices across different districts.
- Identifying trends in high-priced properties and potential outliers in terms of size and price.

Key insight: There is a logical correlation between larger land areas and higher house prices. However, the relationship between land area and building area is less clear, indicating potential discrepancies in the dataset.

## Geospatial Analysis

Geospatial analysis is used to map property prices across districts in Bandung. The project utilizes GeoPandas and a GeoJSON file (from [this GitHub repository](https://github.com/tryfatur/geojson-bandung)) to plot district boundaries and overlay average property prices.

High-priced districts, such as Sukajadi and Cidadap, are known for their higher altitudes and strategic locations near commercial areas, which drive up property values. The analysis also reveals which districts have the most and fewest house listings.

## Technologies Used

- **Python**: Core language for data processing and analysis.
- **Pandas**: Used for data manipulation and cleaning.
- **Seaborn & Matplotlib**: For creating visualizations.
- **GeoPandas**: For geospatial analysis and mapping.
- **Scikit-learn**: For any machine learning tasks (if applicable).

## Acknowledgments
Thanks to KHALEEEL347 on Kaggle for providing the main dataset and introducing thescrapping method, also thanks to tryfatur for providing the GeoJSON file for Bandung's district boundaries. Special thanks to various open-source contributors whose tools and libraries made this analysis possible.
