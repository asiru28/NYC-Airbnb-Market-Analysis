# NYC-Airbnb-Market-Analysis

# Overview/ Introduction

This project analyzes the New York City Airbnb market using data from 2019 listings. The dataset includes information on listing prices, room types, host names, and review dates. The goal is to uncover insights into pricing trends, room type distribution, and review activity to better understand the Airbnb market in NYC.

# Objectives

1. Analyze the distribution of Airbnb listing prices in NYC.
2. Explore the prevalence of different room types (entire homes/apartments, private rooms, shared rooms).
3. Examine review activity to understand the frequency and timing of guest feedback.
4. Provide insights to help hosts optimize their listings and pricing strategies.

# Data Source

The dataset consists of three files:
  1. airbnb_price.csv: Contains listing prices and neighborhood information.
      - Columns: listing_id, price, nbhood_full
  2. airbnb_room_type.xlsx: Contains listing descriptions and room types.
      - Columns: listing_id, description, room_type
  3. airbnb_last_review.tsv: Contains host names and review dates.
      - Columns: listing_id, host_name, last_review

# Tools Used

1. Python Libraries: Pandas, NumPy, Datetime
2. Data Formats: CSV, TSV, Excel
3. Visualization: (Optional – add if you create visualizations)

# Insights

1. Price Analysis:
    - The average nightly price for Airbnb listings in NYC is $141.78.
    - Prices vary significantly depending on the room type and neighborhood.
2. Room Type Analysis:
    - Private rooms are the most common, with 11,356 listings.
    - Entire homes/apartments and shared rooms make up the remaining listings.
3. Review Analysis:
    - Review activity spans from January 1, 2019, to July 9, 2019.
    - Listings with recent reviews may have higher visibility and trustworthiness.
4. Neighborhood Trends:
    - Neighborhoods like Manhattan and Brooklyn have a high concentration of listings.
    - Further analysis could reveal pricing trends and demand patterns in specific neighborhoods.
  
# Key Findings

1. Average Listing Price: The average nightly price for Airbnb listings in NYC is $141.78.
2. Private Rooms: There are 11,356 private room listings, making it a significant portion of the market.
3. Review Activity: The earliest review date in the dataset is January 1, 2019, and the most recent review date is July 9, 2019.
4. Room Type Distribution: The dataset includes three room types: entire homes/apartments, private rooms, and shared rooms.

# Recommendations

1. Pricing Strategy: Hosts with private rooms or shared rooms could consider adjusting their prices to remain competitive, as the average price is heavily influenced by entire homes/apartments.
2. Review Engagement: Hosts should aim to encourage guests to leave reviews, as reviews can improve visibility and trustworthiness on the platform.
3. Market Segmentation: Further analysis could segment the market by neighborhood to identify high-demand areas and optimize pricing strategies.

# How to Use this Repository

1. Clone the repository.
2. Install the required Python libraries (pandas, numpy).
3. Run the Jupyter Notebook (notebook.ipynb) to reproduce the analysis.
4. Explore the dataset and modify the code to conduct further analysis.
