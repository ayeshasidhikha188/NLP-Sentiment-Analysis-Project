# Amazon Fine Foods Reviews Sentiment Analysis
## Project Overview
* This project conducts a comprehensive analysis of the Amazon Fine Foods Reviews dataset, encompassing 568,454 reviews of food products from October 1999 to October 2012.
* The primary objective is to perform sentiment analysis to better understand user sentiments, evaluate product performance, and identify trends in customer feedback.
*  Leveraging MLOps practices, specifically MLflow, ensures efficient management of the machine learning lifecycle throughout this analysis.
![image](https://github.com/user-attachments/assets/8627e5ef-1077-44fd-9a5b-3d4a230c8a14)


## Data Description
* Total Reviews: 568,454
* Unique Users: 256,059
* Unique Products: 74,258
* Key Fields:
* ReviewID: Unique review identifier
* ProductID: Unique product identifier
* UserID: Unique user identifier
* ProfileName: User’s display name
* HelpfulnessNumerator: Helpful votes received
* HelpfulnessDenominator: Total votes on helpfulness
* Score: Star rating (1 to 5)
* Timestamp: Review date and time
* ReviewSummary: Brief review summary
* ReviewText: Detailed review content

## Objectives
* Conduct sentiment analysis to gauge user sentiments regarding products.
* Evaluate product performance based on aggregate ratings and reviews.
* Identify trends in customer feedback over time to inform business strategies.
* Develop predictive models for review scores utilizing advanced Natural Language Processing (NLP) techniques.
* Implement hyperparameter tuning to enhance model performance.

## Methodology
**Data Preprocessing:** Clean and structure raw text data into a well-organized Pandas DataFrame.
**Exploratory Data Analysis (EDA):** Analyze distributions and visualize key metrics to uncover insights.
**Sentiment Analysis:** Classify reviews into positive, neutral, or negative sentiments based on score ratings.
**Model Development:** Develop and train machine learning models to predict review scores, incorporating hyperparameter tuning to optimize performance.
**MLOps Operations with MLflow:** Utilize MLflow for comprehensive tracking of experiments, effective model management, and ensuring reproducibility throughout the machine learning lifecycle.

## Conclusion
This project delivers valuable insights into consumer sentiments and product performance on Amazon by employing advanced NLP techniques to analyze and interpret extensive review data. The integration of MLOps practices, particularly with MLflow, significantly enhances the project's reliability and scalability. MLOps streamlines workflows, fosters collaboration, and facilitates continuous integration and deployment of machine learning models, thereby ensuring sustained model performance and effective management of the analytical process.

