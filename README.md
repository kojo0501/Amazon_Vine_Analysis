# Amazon_Vine_Analysis

## Overivew of Analysis

### Determining Bias
This study seeks to analyze whether being paid for Amazon reviews creates bias in the review. The analysis is conducted on a dataset with 1.7M reviews for videogames. The dataset is filtered to diplay reviews from accounts that have contributed more than 20 reviews, where 50% or more of the reviews were listed as helpful. If separates these between two categories: Vine (paid) and non-Vine (unpaid) reviews. By analyzing whether there's a proportional difference in how these accounts assign 5-star reviews, a possibility for bias can be detected.

## Results

### Comparing Totals and Percentages

* Total Reviews
![image](https://user-images.githubusercontent.com/24308495/149827320-73cc96e4-58da-499a-9985-3a793d78377b.png)



* Total 5-Star Reviews
![image](https://user-images.githubusercontent.com/24308495/149827281-26e7f7df-d451-429a-b99b-4920ee82fc38.png)



* Percentage of Vine vs non-Vine 5-Star Reviews
![image](https://user-images.githubusercontent.com/24308495/149827375-e8bc0417-553c-43d5-bb50-b37ac3c63504.png)



## Summary

### Conclusion 
The disparity in sample size for Vine reviews is problematic for drawing a meaningful conclusion. The total number of Vine reviews were 94, which based on how the data was filtered, might have been produced by four users or fewer. This is being compared with 40,471 reviews, which were produced by significantly more users. To draw any sort of meaningful correlation, we would need a larger sample size for Vine users. It is academically dishonest to draw a conclusion from the behavior of four users because their individual habits may have an outsized impact on the results.

With that understood, there is a ~12 point difference, with Vine users submitting five-star reviews 51% of the time and non-Vine users submitting five-star reviews 39% of the time. If we were to take this data at face-value, and completely disregard the lack of integrity within the sample size, it would suggest the possibility of biased favorable reviews from Vine users.

### Recommendation for Further Analysis
