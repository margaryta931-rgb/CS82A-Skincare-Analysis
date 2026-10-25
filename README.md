# CS82A Final Project: Skincare Price Analysis

## My Question

Are expensive skincare products better rated?

I chose this topic because I am interested in skincare and beauty products. I wanted to know if paying more money means getting a product with better customer ratings.

## Dataset

I used the Sephora Products and Skincare Reviews dataset from Kaggle.

Source: https://www.kaggle.com/datasets/nadyinky/sephora-products-and-skincare-reviews

License: Creative Commons Attribution 4.0 International (CC BY 4.0).

The data was collected in March 2023.

## Data Cleaning

I started with 8,494 beauty products.

- I selected 2,420 skincare products.
- I kept six columns for my analysis.
- I removed 69 products without ratings.
- I checked for duplicates and invalid prices or ratings. I did not find any.
- My final dataset included 2,351 skincare products.

I kept the original price and rating values.

## My Findings

1. The average skincare price was $59.86.
2. The average customer rating was 4.23 out of 5.
3. Affordable products ($44 or less) had an average rating of 4.18.
4. More expensive products (over $44) had an average rating of 4.28.
5. The correlation between price and rating was -0.005, which shows almost no linear relationship.
6. Only 30 products cost more than $300.

## Charts

I created three charts in my Jupyter Notebook:

1. **Price vs. Rating:** I did not see a clear connection between higher prices and higher ratings.
2. **Average Rating by Price Group:** Expensive products had slightly higher average ratings.
3. **Skincare Price Distribution:** Most products were much cheaper than $300.

## Conclusion

I learned that expensive skincare products do not always have better customer ratings. The difference between affordable and expensive products was small. I think people should look at ratings and other information, not only the price.

## Limitations

The data is from March 2023 and only includes Sephora products. Customer ratings are personal opinions and do not measure how well a product works. I also removed products with missing ratings.

## How to Run

1. Download `product_info.csv` or `product_info.csv.zip` from the Kaggle dataset.
2. Open `CS82A_Final_Skincare_Analysis.ipynb` in Google Colab.
3. Run the first cell and upload the downloaded file when prompted.
4. Run the remaining cells in order to see the analysis and charts.

## AI Use

I used ChatGPT for help with Python code.
