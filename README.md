# ACC102_Track2_Airbnb
# ACC102 Track 2: NYC Airbnb 2019 Data Analysis

## 1. Problem & User
This project analyzes the 2019 New York City Airbnb open dataset to understand pricing patterns, geographic distribution, room types, and review activity. The goal is to discover useful insights for travelers, potential hosts, and tourism researchers.

Target users:
- Travelers looking for affordable accommodation in NYC
- Hosts who want to understand market competition and pricing
- Students and researchers studying short-term rental markets

## 2. Data
- Dataset: AB_NYC_2019.csv
- Source: Kaggle (public NYC Airbnb dataset)
- Access date: April 2026
- Content: Information on Airbnb listings across New York City including host details, location, price, room type, minimum nights, number of reviews, and availability.

## 3. Methods (Python Workflow)
1. Import libraries: pandas, matplotlib, seaborn
2. Load the dataset
3. Data cleaning: remove duplicates, drop missing values, filter price outliers (10–1000 USD)
4. Create 4 visualizations:
   - Listings count by area
   - Average price by area
   - Price distribution by room type
   - Price vs number of reviews
5. Generate summary tables for average prices
6. Summarize key insights

## 4. Key Findings
- Manhattan has the highest average price.
- Brooklyn has the largest number of listings.
- Entire home/apartment is the most expensive room type.
- Lower-priced listings tend to have more reviews.

## 5. How to Run
1. Place AB_NYC_2019.csv in the same folder
2. Install required packages:
   pip install pandas matplotlib seaborn
3. Run the Jupyter notebook or Python script

## 6. Product Link & Demo Video
- GitHub Repository: https://github.com/RuizheHuang24/ACC012_Track2_Airbnb.git
- Demo Video: [PASTE YOUR VIDEO LINK HERE]

## 7. Limitations & Next Steps
Limitations: Data is from 2019; no time or seasonal factors included.
Next steps: Add interactive charts, price prediction, or recent data comparison.
