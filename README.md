# Electronic-Products-Survey

![](https://github.com/eloka11222/Electronic-Products-Survey/blob/main/online%20survey.jpg)

## Introduction

The Onyx Data DNA Dataset Challenge is an exciting opportunity for data enthusiasts to showcase their analytical and visualization skills while solving real-world problems. Hosted by Onyx Data UK, this challenge empowers participants to learn together as a community and earn professional recognition.
this month we worked on electronic products ratings and the research questions were:

•	What is the relationship between product ratings and recommendation status?
•	Which brands have the highest average customer satisfaction across different product categories?
•	How do product features (like color or dimensions) influence reviews and ratings?

## Skills displayed
- Wireframig using Figma
- Data analysis
- Data visualization with power bi
- Data cleaning

## Data Sourcing and Cleaning

![](https://github.com/eloka11222/Electronic-Products-Survey/blob/main/Dataset.png)

The data was given in the form of an Excel workbook. The workbook was already cleaned, but the date columns were saved as text. I used the VALUE function to convert the column values to number and saved the columns as dates. I also made sure that all the datatypes were appropriate for the column values. Then I used power query for the transformations.

![](https://github.com/eloka11222/Electronic-Products-Survey/blob/main/Power%20Query.png)

In power query, I was able to split the Weight column by delimiter to be able to extract the numbers from text and define the data types. I then went on to choose only columns relevant to the research objectives. 
I treated blank columns in such a way so as not to lose important data points by eliminating them. 
I filled blanks in numerical columns with 0.

## Data visualization and wireframing

![](https://github.com/eloka11222/Electronic-Products-Survey/blob/main/dshboard.png)

I chose a dark theme for this analysis. Using figma, I was able to build a wireframe to add my visuals. I found out that using wireframes saves time in dashboard development and leaves a neat and well aligned dashboard. This is valuable since a single wireframe and theme can be used repeatedly for multiple dashboards.

## Key questions & findings

•	What is the relationship between product ratings and recommendation status?

![](https://github.com/eloka11222/Electronic-Products-Survey/blob/main/Pie%20Chart.png)

40% of customers who took the review and gave a rating of 3 on average, would not recommend the products to other users while about 59% of customers who took the review and gave a rating of 5 would recommend the products. From this survey, it can deduced that customers who give higher ratings are more likely to recommend the products.

•	Which brands have the highest average customer satisfaction across different product categories?

![](https://github.com/eloka11222/Electronic-Products-Survey/blob/main/producr%20vs%20ratings.png)

I found out that quite a lot of products were given 5 star ratings. But the product with the most overall 5 star ratings was Kicker

•	How do product features (like color or dimensions) influence reviews and ratings?

![](https://github.com/eloka11222/Electronic-Products-Survey/blob/main/Rating%20colors.png)

Darker colors seem to have higher ratings than brighter colors since colors that have black in them seem to have ratings between 5 and 4 on average.

Other findings

•	7299 individual responses were recorded
•	4341 people found the reviews helpful
•	The average weight of a product was 5.79 pounds
•	On average, the products were given a 4-star rating.
•	The most number of 5-star ratings were given in 2007 
•	In 2009, the products received the lowest ratings with an average rating of 3

Conclusion
This project was an interesting one. It pushed me to greatly improve my visualization skills and also helped me improve my analytical skills in total.
you can interact with the live dashboard [here](https://app.powerbi.com/view?r=eyJrIjoiODRkZTQ3MTQtMjUwZC00YmUwLTk2MzAtY2EwNTI1NmRmZmE5IiwidCI6Ijk0OTg2MDlmLTAxNWMtNDgwMS05MjA4LWNiMzdjYWFkMzc1YSIsImMiOjZ9)
