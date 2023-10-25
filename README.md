# H-M-Personalized-Fashion-Recommendations

This GitHub repository is dedicated to the H&M Personalized Fashion Recommendations Challenge. The goal of this task is to develop product recommendations based on data from previous transactions, customer data, and product metadata. These recommendations will help enhance the shopping experience for customers and contribute to sustainability efforts by reducing returns and minimizing emissions from transportation.

Challenge Description

H&M Group is a renowned family of brands and businesses with a global presence, offering a wide range of fashion products through both online markets and physical stores. With the vast array of choices available to customers, it can be challenging for them to quickly find products that interest them. To address this issue, product recommendations are crucial. This task to leverage transaction data, customer metadata, and product information to predict the articles that each customer is likely to purchase in the 7-day period immediately after the training data ends.

The provided data includes:

transactions_train.csv: This file contains the purchase history of customers over time. It includes information about the purchases made by each customer for each date, along with additional details. Duplicate rows correspond to multiple purchases of the same item.

articles.csv: This file provides detailed metadata for each article_id available for purchase, including information such as garment type and customer age.

customers.csv: This file contains metadata for each customer_id in the dataset.

images: This folder contains images corresponding to each article_id, organized in subfolders based on the first three digits of the article_id. Not all article_id values have corresponding images.


