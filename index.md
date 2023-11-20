# DSC180A Methodology Assignment 5

Name: Maximilian Wei <br>
Email: mawei@ucsd.edu <br>

Section: Research on Factors Influencing Business Growth (B10)  <br>
Mentor: Naomi Young (SANDAG) <br>

**What is the most interesting topic covered in your domain this quarter?** <br>
I believe the most interesting topic we have covered so far in our domain, has been the clustering algorithm SANDAG used to determing their employment centers. Data used were building-level employment estimates. All local-maxima were chosen as starting centroids which were grown to include any nearby parcels over a given employment density threshold.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.** <br>
A potential path we could take for our Quarter 2 project, would be to replicate SANDAG employment forecasts, which are currently calculated with an array of domain specific formulas, with some sort of machine learning model. Doing so could allow SANDAG and other governmental associations to output employment forecasts more frequently, than the current 4-year cycle, and potentially provide more accurate forecasts than handcrafted calculations, by including less human-interpretable/expectable factors.

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?** <br>
Our current Quarter 1 approach has been to work off of the US Census' County Business Patterns data, which records the number of businesses in each zipcode, by augmenting it with outside data to create more features that may be helpful for prediction. Our current approach to determing good features, has been through finding supporting papers on theoretical economics, and inquiring our mentor's opinion. One change that could be made to our current Quarter 1 approach could be to focus more on quantitative measures to validate the efficiency of the features we have produced/transformed from our data. One way we have thought to do this has been to peek into the converged coefficients of simple linear regression models trained on the data. This, however, may not be the most optimal approach.

**What other techniques would you be interested in using in your project?** <br>
Since the problem of forecasting business growth is inherently one of time-series analysis, I hope to leverage this opportunity to learn more about time-series prediction and deep-learning implementations through LSTMs. 