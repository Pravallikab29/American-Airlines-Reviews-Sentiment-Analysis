# American-Airlines-Reviews-Sentiment-Analysis
Situation:
American Airlines sought to gain insights into customer perceptions of their service quality during flights. To achieve this, they decided to analyze customer reviews collected from the Skytrax website.

Task:
The main objective was to conduct sentiment analysis on the customer reviews to identify areas requiring improvement. This involved gathering and preprocessing the data, conducting sentiment analysis, and extracting key insights.

Action:

* Data Collection: Customer reviews were scraped from the Skytrax website using the Beautifulsoup method from the NLTK library.
* Data Preprocessing: The collected data was cleaned to remove missing values and underwent preprocessing steps such as text formatting, lemmatization, and removal of stopwords.
* Sentiment Analysis: VADER, a rule-based sentiment analysis tool, was applied to estimate the percentage of positive, negative, and neutral comments in the dataset.
* Word Frequency Analysis: N-gram analysis was conducted to identify the most frequently occurring words in the reviews, shedding light on the primary areas of customer dissatisfaction.

Result:
The analysis revealed that a significant portion of customers, accounting for 63.3%, expressed negative sentiments towards American Airlines. Additionally, a striking 69% of customers assigned a mere 1-star rating. The primary areas of dissatisfaction centered around customer service and the quality of snacks and beverages offered during flights. These findings provide actionable insights for American Airlines to prioritize and address areas in need of improvement, ultimately enhancing the overall customer experience.
