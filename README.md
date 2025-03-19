# Overview

This project performs sentiment analysis on customer comments and ratings for various brands and items. The dataset consists of 14,282 comments and covers 192 brands. The goal is to derive insights about customer sentiment and brand perception based on textual reviews and numerical ratings.

**Dataset**

#Total Comments: 14,282

#Total Brands: 192

Data Sources: Customer reviews from the given dataset. [Consumer Sentiments and Ratings](https://www.kaggle.com/datasets/kapturovalexander/consumer-sentiments-and-ratings) 

**Data Format:**

Comment: Textual feedback from customers.

Rating: Numerical rating given by the customer.

Brand: The brand associated with the review.


<br>
<br>

**Methodology**

*Data Cleaning*:

Performed in **Microsoft Excel**.

Removed duplicates and handled missing values.

Standardized text formatting.

*Translation*:

Conducted in Google Sheets using the **GOOGLETRANSLATE** function.

*Sentiment Analysis in Power BI*:

Implemented sentiment scoring within **Power BI** using integrated text analytics.

Created visualizations to represent sentiment distribution across brands and ratings.

*Evaluation and Insights*:

Analyzed sentiment trends using Power BI dashboards.

Identified key themes and patterns in customer feedback.

<br> 

**Results and Insights**

Sentiment distribution across brands.

Correlation between ratings and sentiment scores.

Top brands with the highest and lowest sentiment scores.

Common positive and negative keywords used in reviews.

<br>

**How to Run the Project**

*Prerequisites*

Ensure you have access to:

Microsoft Excel (for data cleaning)

Google Sheets (for translation)

Power BI (for analysis and visualization)

Running the Analysis

Open the dataset in Excel and ensure data is cleaned properly.

Translate non-English comments in Google Sheets using:

=GOOGLETRANSLATE(A2, "auto", "en")

Import the cleaned and translated dataset into Power BI.

Perform sentiment analysis using Power BI’s text analytics capabilities.

Generate reports and visualizations within Power BI.


<br>

**Contributors**

*Pratham Dhanesha*

dhanesha151001@gmail.com <br>
[Portfolio](https://dhanesha151001.github.io/portfolio/)


*License*
This project is licensed under the GNU General Public License v3.0.
