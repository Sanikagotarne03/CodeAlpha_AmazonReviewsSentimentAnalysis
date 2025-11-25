Amazon Product Review Sentiment Analysis

📘 Project Overview

This project performs sentiment analysis on Amazon product reviews using Natural Language Processing (NLP).
The goal is to classify customer reviews into positive, negative, or neutral sentiments and extract key insights to help understand customer satisfaction and improve product decisions.

🎯 Objectives

Perform data cleaning and text preprocessing

Analyze reviews using NLP-based sentiment analysis

Classify reviews as positive, negative, or neutral

Visualize sentiment distribution

Provide insights for business decision-making

📂 Dataset Source

Amazon Product Reviews Dataset from Kaggle
https://www.kaggle.com/datasets/bittlingmayer/amazonreviews

This dataset contains millions of reviews with ratings, text, timestamps, and helpfulness metrics—ideal for sentiment classification and NLP.

📑 Dataset Features
| **Feature**                | **Description**                                              |
| -------------------------- | ------------------------------------------------------------ |
| **Id**                     | Unique identifier assigned to each review                    |
| **ProductId**              | Unique code representing each product                        |
| **UserId**                 | Unique identifier of the customer/reviewer                   |
| **ProfileName**            | Name of the reviewer                                         |
| **HelpfulnessNumerator**   | Number of users who found the review helpful                 |
| **HelpfulnessDenominator** | Total number of users who evaluated the review's helpfulness |
| **Score**                  | Product rating given by the user (1 to 5)                    |
| **Time**                   | Timestamp of when the review was posted                      |
| **Summary**                | Short summary/title of the review                            |
| **Text**                   | Complete review text provided by the customer                |


🛠 Tools and Technologies
| **Technology**            | **Purpose**                                                 |
| ------------------------- | ----------------------------------------------------------- |
| **Python**                | Programming and data analysis                               |
| **Pandas, NumPy**         | Data cleaning, manipulation, and processing                 |
| **NLTK, TextBlob, VADER** | Sentiment analysis and Natural Language Processing (NLP)    |
| **Matplotlib, Seaborn**   | Data visualization and insights representation              |
| **Jupyter Notebook**      | Development, experimentation, and documentation environment |

🔄 Analysis Workflow

Import and explore dataset

Clean data and remove duplicates

Text preprocessing (tokenization, stopword removal, stemming)

Sentiment classification (positive/negative/neutral)

Visualize results and insights

📊 Key Insights

Majority of reviews were positive, showing high customer satisfaction

Negative reviews mostly highlighted issues in delivery, packaging, or product quality

Strong correlation observed between ratings (Score) and sentiment labels

Helpful reviews were mostly descriptive and detailed

📝 Conclusion

Sentiment analysis helps understand customer opinions and improves decision-making for product development, marketing, and customer service.
This project demonstrates how NLP can be applied to analyze real-world review data.

🙋 Connect With Me

Sanika Gotarne

LinkedIn: https://www.linkedin.com/in/sanika-gotarne-451462290
