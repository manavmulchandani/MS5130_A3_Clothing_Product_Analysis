# MS5130_A3_Clothing_Product_Analysis

This repository contains the R code and analysis for the MS5130 Assignment 3. The assignment is focused on analysing an ecommerce website's clothing products. The analysis utilizes datasets related to clothing products, their brands, pricing, customer reviews, and brand origin locations.

## Overview

The clothing products analysis using multiple datasets covers:

- Identification of expensive and budget-friendly brands.
- Products distribution across genders.
- Color popularity among products.
- Sentiment and review analysis.
- Creating wordcloud of category.
- Changes in average product prices over time.
- Visualization of brand origins on a world map.

## Datasets

The analysis utilizes the following datasets:

- `myntra_products_catalog.csv`: Contains product catalog data.
- `Product_Detailed_2.csv`: Detailed product information including pricing and ratings.
- `Product_Reviews_3.csv`: Customer reviews and sentiments.
- `Location_of_brands.csv`: Origin locations for various brands.

## Tools and Libraries Used

- **R**: The analysis is conducted entirely in R.
- **Libraries**: ggplot2, dplyr, tidyr, stringr, readr, tidytext, plotly, wordcloud, quanteda, leaflet, and tidygeocoder.

## Running the Analysis

To run this analysis, ensure you have R installed along with the necessary packages mentioned above. Clone this repository, and run the code in the provided QMD file. The datasets should be placed in the same directory as the QMD file or adjusted paths within the code.

## Visualizations

The project includes various visualizations like bar charts for gender and color distributions, histograms for sentiment analysis, and Leaflet maps for geographical data presentation.
