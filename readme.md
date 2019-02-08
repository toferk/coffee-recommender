# Coffee Recommender
#### By: Tofer Kim

## Executive Summary
   This project features a coffee recommender system based on data scraped from www.coffeereview.com. The system considers 4,887 unique coffees and recommends a coffee based on the cosine similarity of specified features. The system can be customized to base recommendations from three criteria: text description, ratings & types, and a combination of the two. Furthermore, the system is able to recommend the highest rated within a defined range of similar coffees, or the overall most similar coffee.   
   The system can only provide results for coffees present in the dataset using it's unique webpage slug. The dataset includes coffees that were reviewed as far back as 1997 and, unfortunately, may no longer be available.  
Next steps involve conducting A/B hypothesis testing to determine usefulness of the recommender system and further tune the considered criteria--potentially consulting with coffee-tasting experts as well as gathering feedback from users. 

### Contents
- Code  
    1. Web-scraping: Collects data from www.coffeereview.com and extracts relevant information using BeautifulSoup and RegEx. 
    2. Data cleaning & EDA: Cleans and visualizes text descriptions using Latent Dirichlet Analysis. Explores feature distributions and handles missing values. Also includes Data Dictionary. 
    3. Cosine Similarity: Conducts final transformations of the data (StandardScaler, TF-IDF, and TruncatedSVD transformations) in order to calculate cosine similarities.  Includes test outputs from the recommender system. 
- Data
    1. coffee.csv: Original web-scraped data
    2. coffee_clean: Clean and complete data for each coffee
    3. coffee_id: Contains each coffee's name, roaster, and webpage slug for identification



- Images
- Presentation
