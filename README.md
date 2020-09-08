# SF-EMS-Response-Prediction

### Goal
- Using machine learning, I will aim to predict the response time for an EMS to get on-scene to a call. Comparing multiple models, there would be both inferential and predictive value in assessing what factors contribute most to a higher response time, and using a time-based feature engineering to predict when response rates will be highest, with the aim to increase the saturation of EMS vehicles during those times.

### How has this been solved?
- This problem has been addresed in multiple studies, but with many of them either data, or based on different areas. The following two articles are from 1978, and an analysis on rural areas, respectively: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1072082/, http://www.users.miamioh.edu/smuckebj/pub_2018+_Hillenburg_etal.pdf

### What is new about my approach
- I believe my comparison of multiple different models will be helpful, as it seems other studies tended to rely solely on linear regression. Additionally, it seems that different areas may have unique geographical aatributes that are difficult to model. Because of this, making a model based on San Francisco specifically will be more beneficial than trying to relate an adjacent study to the city.

### Who Cares?
- If I am successful, this could further provide information on which factors contribute most to a higher response rate, and therefore a higher mortality rate, in EMS services. This information could be used to predict and prepare for times of high saturation (which would presumably lead to higher response rates), and to make structural changes to the EMS system that addresses the siginificant features. 

### How will I present?
- I will present my project through github, and may try to create interactive statistical models through jupyter notebooks to compare against neighborhoods and other features.

### Data source
- It is the data available from the SF Gov open source EMS data, containing approx. 5.32 million instances across a 20 year time period. 

### Potential Problems
- The obvious factors in EMS responses have been addressed and least on a qualified level, so I may not find much correlation that provides useful information.

### Next thing?
- Feature engineering the data
