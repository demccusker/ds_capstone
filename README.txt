### Project Overview 
In this project, I'm using the most recent data from the US Department of Education's College Scorecard for the 2021-2022 school year and supplementing it with previous years' data to investigate a number of questions. Find the data sets used here: https://collegescorecard.ed.gov/data 
Read the full write up of the project here: https://darcymccusker.substack.com/p/understanding-the-college-scorecard

The questions I'm interested are as follows:
>  1. How does the median debt at graduation vary across different Carnegie classifications of institutions?
>  2. Are there regional trends in graduation rates?
>  3. Does the selectivity of an institution (e.g., acceptance rate and SAT scores) correlate with its graduation rates?
>  4. Do public vs. private vs. for-profit institutions show distinct patterns in costs, debt, or graduation rates?
>  5. What factors drive graduation rates?


### Conclusions
In conclusion, I was able to answer several questions about how schools compare across the College Scorecard 
that may be able to help a high school junior or senior decide on the best college for them. Location does 
matter, but I would argue that retention rate is a better predictor of graduation outcomes than selectivity is; 
retention rate came out as the clearest factor in the random forest model, while the linear relationships between
 SAT average and admissions rates were not particularly strong. Finding a school with high retention rates 
is important for graduation, because if students stay year over year, they are more likely to graduate. 
Choosing a school with a strong retention rate is important for increasing the odds of any given student graduating. 

The type of school was not a strong predictor for graduation rates, but it does matter for amount of debt, 
median earnings, and total cost. Private non-profit schools have higher median earnings (including having 
much higher maximum values), but that corresponds to a higher cost of tuition and higher debt after leaving 
the school.  Public and private for-profit institutions have somewhat lower median earnings ten years after 
graduation, but that is counterbalanced by generally lower tuition costs and thus lower loan balances at the 
end of school. How one decides to choose between each institution type depends on what one weighs as more 
important: higher earning potential with higher debt, or lower debt and (somewhat) lower earning potential. 

Additionally, the type of school in terms of residential vs non-residential also impacts debt after leaving 
school. Shorter, non-residential program graduates have lower debt loads. Again, what a high school senior 
does with this information depends on what they value: someone who values the residential experience highly 
may still want to attend such an institution, even though the average grad has more debt. 


### Libraries used
> pandas, version 2.2.0 </br>
> matplotlib, version 3.8.2 </br>
> seaborn, version 0.13.2 </br>
> scikitlearn, version 1.4 </br>
> numpy, version 1.26.4 </br>
> scipy, version 1.13.0  </br>


### Acknowledgements
Find the data sets used here: https://collegescorecard.ed.gov/data 
This data is licensed under a Creative Commons Attribution 4.0