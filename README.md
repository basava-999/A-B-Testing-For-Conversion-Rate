# A-B-Testing-For-Conversion-Rate

Packages/Libraries imported :
Numpy, Pandas, Scipy, Statsmodels

Primary Metric : Conversion rate = no. of conversion / total no of visitors

Scenario :
This Testing is about two versions of a product being invested by a Product Team at a Online E-Commerce Company. The UI/UX team really worked hard on a new version of the product page, with a hope that will lead to a higher conversion rate. The Product Manager that told that the CR on the webpage is being 13% on average throughout the year, and the team would be satisfied with a 2% lift upon previous CR, meaning that the new UI/UX of the web page is success if it raises conversion rate to 15%.

Conclusion:
Since our P -value=0.6656 is way above our =0.05, we cannot reject the null hypothesis , which means that our new design did not perform significantly different (let alone better) than our old one.

Additionally, if we look at the confidence interval for the treatment group ([0.1144, 0.1306], i.e. 11.44% - 13.06%) we notice that:

1. It includes our baseline value of 13% conversion rate
2. It does not include our target value of 15% (the 2% uplift we were aiming for)

This conveys that it is more likely that the true conversion rate of the new design is similar to our baseline or less , rather than the 15% target we had hoped for. This is further proof that our new design is not likely to be an improvement on our old design.
