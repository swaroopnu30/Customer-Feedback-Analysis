# **Urban Company Customer Feedback Analysis Dashboard (Power BI)**



This project analyzes customer reviews for Urban Company and converts them into an interactive Power BI dashboard. It focuses on understanding overall sentiment, rating patterns, and key customer pain points between 01/10/2021 and 09/09/2023.



## **Dataset**



* Source: Urban Company Customer Feedback Dataset (OpenDataBay – Free Dataset Library).
* Size: 189 customer reviews after cleaning.
* Columns included: Date, Time, Ratings, Review\_Title, Review\_comment.
* All data used strictly for learning and portfolio purposes.



## **Tools and Skills Used**



* Power BI Desktop
* Power Query for cleaning and transformation
* Data modeling and custom calculated columns
* Dashboard design using cards, donut chart, bar chart, line chart, tables, and slicers



## **Data Preparation (Power Query)**



* Removed duplicates and blank entries.
* Standardized text by converting Review\_Title and Review\_comment to lowercase.
* Created a Combined Review column (title + comment).



Added a Sentiment column based on Ratings:

* 4–5 → Positive
* 3 → Neutral
* 1–2 → Negative



## **Dashboard Features**



Sentiment Card showing dominant sentiment (Negative).



Donut Chart – Count of Reviews by Sentiment:



* Negative: 168 (88.89%)
* Neutral: 13 (6.88%)
* Positive: 8 (4.23%)



Column Chart – Average Rating by Sentiment



* Negative: 1.03
* Neutral: 3.00
* Positive: 4.38



Line Chart – Ratings Over Time (2021–2023)



Shows consistently low ratings with occasional peaks.



Table View – Review text, Rating, Sentiment, Date.



Slicers – Sentiment filter and Date range filter.



## **Key Insights**



* Feedback is heavily negative: 88.89% of all reviews.
* Strong sentiment polarization: Negative reviews average 1.03, positives average 4.38.
* Low ratings persist across the entire two-year period.



Common negative themes:

* &nbsp;     Unprofessional/late technicians
* &nbsp;     Cancellations and rescheduling
* &nbsp;     High or unclear charges
* &nbsp;     Ineffective warranty/refund support



## **Recommendations**



* Improve technician training, screening, and monitoring.
* Strengthen scheduling reliability and reduce last-minute cancellations.
* Make pricing transparent to avoid “hidden charge” complaints.
* Provide a simple, trackable process for warranty/refund requests.
* Review sentiment monthly using the dashboard to measure improvements.
