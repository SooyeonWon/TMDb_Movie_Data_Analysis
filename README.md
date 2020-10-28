# TMDb Movie Data Analysis
Standard Process of Data Analysis 

#### Sooyeon Won 

### Keywords 
- Analysis with Real-World Data
- Data Cleaning 
- Analytic Frameworks
- Exploratory Data Analysis 
- Trend Analysis based on Rolling Average 


## Summary of Findings 

In this analysis, I have investigated the movie dataset collected from 1970 to 2015. For the comparable analysis over the years, adjusted budgets and adjusted revenues are taken. Movies with zero budgets are practically unreliable, so they are dropped at the beginning of the investigation.

- Among twenty genres, the heyday of each genre is all different. For example, the genre music dominates in 2015, and Adult genre dominated in 1970. Drama was the steadily best-loved genre over the years. Also, there are several years that comedy genre was more popluar than drama.
- The properties such as popularity, running time, vote and budget of movies are positively related with the high revenue of movies.
- The average revenue of movies which belong to the two genres: Drama or Comedy is significantly less than the revenue from non-Drama or non-Comedy movies, at a significant level 0.05.
- While the number of movies released in each year is growing fast and the movies enjoy the rise in its popularity over the years, the average revenue of movies released in individual year is gradually decreasing since 1980.
- One limitation of this analysis is the comparisons between genres. A majority of movies are consisted of the mixture of several genres. Since genres are not completely independent, it is difficult to measure the average popularity / revenue of each single genre and compare one another. Also, there might be able to exist the combination effects. For example, drama is the most popluar genre from year to year because drama can easily combined with other genres, such as action-drama, thriller-drama, comedy-drama and so on.


## References 
[Moving Average with Pandas](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.rolling.html)<br>
[T-test with Scipy](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.ttest_ind.html)
