# Analyze-A-B-Test-Results
This is project is about understanding the results of an A/B test run by an e-commerce website. The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. the goal is to work through this notebook to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.
# Data Cleaning
>Based on data cleaning code there are no duplicate rows or missing data in our dataset
# Part I - Probability
>after calculating the brobablity of conversion of the two pages we found the following:       
there is  no sufficient evidence to say that the new treatment page leads to more conversions   
as the probabity of the conversion in control page is slightly higher than conversion in  treatment page   
and for practical there is no signficance between the two pages as the differenc in probablity is so small. 
# Part II - A/B Test
Based on A/B test the new page has no effect on conversion rate  and  from logistic regression the country has no effect on conversion rate too so the website should keep the old page or run the experiment for more time
# Part III - A regression approach
>my hypotheses in the Part II and my regression model agree with each other and the final result that we fail to reject the null hypothesis so the new page that customer recieves has no effect on convesion rate
># Conclusions
***for statistical significance:      
Based on A/B test and logistic regression the new page has no effect on conversion rate  and  from logistic regression the country has no effect on conversion rate too so the website should keep the old page or run the experiment for more time   
for practical significance:   
the experiment should run for a longer time than 22 days so we can judge the new page*** 
