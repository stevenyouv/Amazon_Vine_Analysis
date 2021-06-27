# Amazon_Vine_Analysis

## Project Overview

For this project a data set from Amazon reviews for video games was selected for analysis to determine whether there is a favorable review bias from Vine members versus non-Vine members.  To accomplish this, Pyspark was used to perform the ETL process by extracting the data, transforming the data, and connecting to teh database that was generated through the webserver

## Results

![image](https://user-images.githubusercontent.com/78937719/123558519-4e90af00-d75c-11eb-8d40-f4e8c6774ed4.png)

### How many Vine Reviews and non-Vine reviews were there?

- There were a total of 40,471 unpaid reviews
- There were a total of 94 paid reviews

### How many reviews were 5 Stars? How many non-Vine reviews were 5 stars?
- There were 15,556 non-paid 5 star reviews
- There were 48 paid 5 star reviews

### What percentage of Vine reviews were 5 stars?  What percentage of non-Vine reviews were 5 stars?
- 51.1% of paid reviews were  5 star
- 38.7% of unpaid reviews were 5 star

## Summary  
With 51.1% of the reviews in the Vine program being 5 stars versus 38.7% non-Vine reviews being 5 stars, there is a clear indicator that there is a positivity bias for reviews in the Vine program.  
An additional analysis of the statistical distribution (mean, median, and mode) of the star ratings for the Vine versus Non-Viine reviews could be run to determine the impact of Vine reviews.  
