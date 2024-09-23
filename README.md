# Guiding Radiance: Making Informed Skin Care Decisions by Navigating Ingredients and User Experiences in SPF Face Creams

## Objective
This project seeks to evaluate how well the marketing claims of the top ten SPF face creams of 2024 align with real-world user experiences. Using sentiment analysis and topic modeling, it explores consumer perceptions and provides insights into whether these products deliver on their promises. The ultimate goal is to help consumers make informed skincare decisions.

## Data and Tools
### Data Sources:
  1. The Independent: Web-scraped reviews of the top ten SPF face creams of 2024.
  2. Reddit API: User reviews from subreddits such as SkincareAddiction and AsianBeauty.
### Tools & Methods:
  - Python: For web scraping and data processing (libraries: BeautifulSoup, Pandas).
  - NLP Techniques: Sentiment analysis (VADER) and topic modeling (LDA).
  - TF-IDF Vectorization & KMeans Clustering: To quantify text and group comments by themes.
### Visualization: 
  - Barplots and word clouds to visualize common words, themes, and sentiment.

## Key Question
To what extent do the advertised benefits of popular SPF face creams align with their actual formulations and real-world user experiences, and how can this information guide consumers in making informed choices about SPF products?

## Results
### Sentiment Analysis: 
The reviews exhibit a broad spectrum of sentiment, from positive to negative, with notable differences between marketing claims and user feedback. For instance:
  - Products like La Roche-Posay Anthelios received positive comments for affordability and effectiveness.
  - Some products, like Chanel UV Essential, faced criticism for leaving a white cast or greasiness.

### Topic Modeling: 
The LDA model identified recurring topics in user discussions:
  - Affordability and effectiveness were prominent for products like Garnier Ambre Solair.
  - Negative experiences such as oily texture, white cast, and breakouts were frequent across many products, indicating discrepancies between marketing and reality.

### Cluster Analysis: 
The ingredients were analyzed in clusters, revealing similarities between products like Supergoop Mattescreen and Glossier Invisible Shield, which share common components linked to UV protection.

## Conclusion
This analysis reveals that while SPF face creams often meet their marketing claims regarding UV protection, user experiences suggest that issues like texture, skin reactions, and residue are common. These insights emphasize the importance of real-world user feedback for skincare decisions, encouraging consumers to look beyond marketing promises when choosing SPF products.
