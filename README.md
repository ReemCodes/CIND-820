Airbnb Toronto Sentiment Analysis

**Project Overview**

In this project, I conduct a comprehensive analysis of Airbnb listings and reviews in Toronto to understand guest preferences and factors influencing their satisfaction. 
Utilizing advanced text mining and sentiment analysis techniques, I aim to decode the nuanced feedback provided by guests in their reviews and correlate these insights with quantitative ratings of listings.
This research is expected to unveil key determinants of guest satisfaction, providing actionable insights for Airbnb hosts to improve their services and for potential guests to make informed decisions.

**Datasets**

This project utilizes two primary datasets from Inside Airbnb:

Listings Dataset: Contains detailed information on Airbnb listings in Toronto, including attributes like price, location, amenities, and host ratings. http://data.insideairbnb.com/canada/on/toronto/2024-02-14/data/listings.csv.gz

Reviews Dataset: Comprises guest reviews for the listings, providing rich textual data for sentiment analysis and text mining.
http://data.insideairbnb.com/canada/on/toronto/2024-02-14/data/reviews.csv.gz

**Repository Contents**

_'README.md'_ Overview of the project, datasets, and instructions for replicating the analysis.

_'notebooks/'_ Jupyter Notebooks detailing each step of the analysis:

    'REVIEWS_initial_analysis.ipynb' Initial exploratory data analysis of the reviews dataset.
    'LISTINGS_initial_analysis.ipynb' Initial exploratory data analysis of the listings dataset.
    'REVIEWS_Cleanup.ipynb' Notebook dedicated to the cleaning and preprocessing of review data.
    'Text_Analysis_And_Model' Notebook for sentiment analysis, emotion extraction, topic modeling, and inital model
    'MODEL' Notebook that includes model(s) and evaluation
    
**Data Collection**

Data utilized in this project is sourced from Inside Airbnb, covering comprehensive listings and reviews data specific to the Toronto area. 

**Methodology**
The methodology unfolds in several phases:

_Data Import and Quality Check:_ Importing datasets into Python and conducting quality checks to ensure data reliability.

_Exploratory Data Analysis (EDA):_ Separate EDA for listings and reviews to understand dataset characteristics and potential correlations.

_Data Preprocessing:_ Cleaning and preprocessing review texts for further analysis.

_Sentiment Analysis and Emotion Extraction:_ Applying NLP techniques to analyze the sentiment and emotions expressed in reviews.

_Text Mining and Topic Modeling:_ Identifying key themes and patterns within the reviews.

_Model Building and Evaluation:_ Developing predictive models to associate review texts and sentiments with listing ratings.



