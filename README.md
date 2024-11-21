# Analyzing Consumer Sentiment on Reddit to Address Constellation Brands' Wine Sales Challenge
## Company Overview
Constellation Brands is a leading beverage company specializing in beer, wine, and spirits. Recently, the company divested its mainstream wine portfolio to focus exclusively on the premium wine segment. However, this strategic shift has coincided with declining wine sales, posing a challenge for the company to understand and adapt to evolving consumer preferences effectively.
## Problem Statement
**Can Reddit topics be effectively utilized as a source of data to predict consumer sentiment towards a specific product?**
## Methodology
### Data Preprocessing
- **Text Normalization:** Utilized **WordNetLemmatizer**.
- **Feature Extraction:** Applied **CountVectorizer**.
- **Highlighting Significant Terms:** Incorporated **Term Frequency-Inverse Document Frequency (TF-IDF)**.
### Modeling
- Evaluated multiple machine learning models using **GridSearch** to optimize hyperparameters.
- Selected the best-performing model based on accuracy and relevance to sentiment analysis.
## Findings and Insights
### Key Discussion Topics on Reddit
#### 1. Wine
- Reddit discussions leaned heavily towards **red wine**, particularly **Pinot Noir**.
  - **Pinot Noir Characteristics:** A light-bodied red wine with soft tannins, red fruit flavors (like cherry and raspberry), and earthy undertones. It is versatile, appealing to both casual and seasoned wine drinkers.
  - **Insight:** Pinot Noir could be a strategic focus area within Constellation Brands’ premium wine portfolio.
#### 2. Beer
- Beer remains the company’s largest revenue contributor and warrants attention.
- Reddit users discussed **Ale** extensively, especially those made from **Hops**.
  - **Ale Characteristics:** Known for a sweet taste and distinct hop bitterness. Aesthetic elements like **foam** were frequently mentioned, emphasizing the importance of visual appeal in beer branding.
## Limitations
- **Limited Data:** The analysis is constrained by the volume of wine-related discussions available on Reddit.
- **Representation Bias:** Not all wine consumers actively participate in Reddit discussions, potentially skewing sentiment analysis results.
## Further Research
1. **High-End Market Analysis:** Investigate consumer preferences and purchasing behaviors within the luxury wine market.
2. **Broader Data Collection:** Expand research to include data from other platforms like Twitter, Instagram, and wine-specific forums to ensure more comprehensive insights.
## Conclusion
This project demonstrates the potential of Reddit as a data source for sentiment analysis. By leveraging NLP techniques, Constellation Brands can gain actionable insights into consumer preferences, helping them refine their premium wine offerings to better align with market demand.
