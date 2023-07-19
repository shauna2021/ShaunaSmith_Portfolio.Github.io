# Data Dream Jobs Project
![image.png](attachment:image.png)

> #### Author: Shauna Smith (2023)

## History/Business Problem 
    
    Project Topic - "Predicting Job Type by the select desirability of lifestyle expectations to best serve Your university Major and ultimate career goals."  
    
At Kukis-Garo we are the country's leading innovator, acting as the top headhunter for Universities and the like. We have a long history of dealing with hunting heads, and in the modern world, we are just as excellent at hunting. Kukis-Garo works hard to find the greatest advantages for implementing both efficient and provable metrics to acquire the greatest minds from the sought-out greatest heads to apply towards any goal. 
    
  ![image-2.png](attachment:image-2.png)
    
For Universities, we pride ourselves in finding great students and developing their drive towards a career-based goal education. We desire to see fulfillments from advanced learning all the way into career fields of their choice. The proposal at hand seeks to deliver just such an initiative and provide a method for predicting the job types as a motivationally based expectation of commitments from the student's preferences. To best do this, we are utilizing a means of predictive analytics & employing ML, to better offer comparable real-world data that predicts what you need for success. Ultimately, this data collection and model will yield predictions that better suit the needs of career types. It is derived from the selective input expectations customized for each student and sourced for each teacher or program offering. In turn, this should help maintain enrollment retentions to better improve graduation rates on the whole. As a collective assessment process, it will implement metrics of improvements that will encourage future student prospects and beneficially increase the reputational outlooks of each University that endorse such methods.

## Data Explanation(Data Prep/Data Dictionary/Etc.) & Methods

The Dataset used for this framework was derived from the open-source Kaggle found at the following link: https://www.kaggle.com/datasets/iamsouravbanerjee/data-science-salaries-2023

This dataset consisted of Data Science related to Job types and their corresponding features. Some of the features used were Salary, Employment Type, Expertise Level, and Job Titles. All these features are relegated from a relevant given time span of 2020-2023 and thus appropriately allow for a real-world framework as conscripted to current estimations. This practice Model will serve to categorize data-related fields of education and directly hone in on servicing future Data Scientist related programs or other such top data technology-related studies.  

For preparation purposes, we started with a relatively clean dataset that had no missing values and we chose to drop the features that were redundant or unusable for our intended purpose. This led to the elimination of some features such as country-based metrics for varying types of currency and the like. 
    
Then, by assigning renamed delineation methods to the values in the working features we formed a better machine-suited dataset. This consisted of taking the unique values and subgrouping them into qualities represented by the whole. Such an example of this was regarding Expertise Level, which it was broken down into numerical replacements of 1 or 2(Higher expertise vs lower expertise). This assignment was derived from an original starting measurement of 'Expert','Director', 'Intermediate', 'Junior' from which the original data observations accounted for. Similar steps were taken to Company size or others, but some of these subsequently were shown as features lacking importance, and therefore they were dropped from the final working data frame in the end. 

### Feature Importance from DTC and RF
   ![image-4.png](attachment:image-4.png)

   ![image-3.png](attachment:image-3.png)

### Data Dictionary:

| Feature        | type      | # used +/-  |
|----------------|-----------|-------------|
|Job Title       | string    |  as+"Job"   |
|Employment Type | string    |-(redundant) |
|Experience Level| string    |-(redundant) |
|Expertise Level | integer   |as+"Exper..."|
|Salary in USD   | integer   | as+"Salary" |
|Company Size    | string    |-(redundant) |
|Year            | integer   |  as+"year"  |


Several data prepping approaches were employed to the dataset during the discovery process and steps to better adjust the dataset features to work with the elements related to the model's preferences were applied as needed to best develop the output. The application for predictive analysis using Random Forest and Decision Tree Classifiers were employed. This gave a better insight into a given feature's importance. Final additions for developing a linear regression analysis aided in building useable visualizations but yielded extremely low accuracy predictions as a model construct. 


## Analysis/Conclusions With Assigned Assumptions & Limitations Or Challenges

In the end, the best performance was gained from the DTC(Decision Tree Classifier) and even though the accuracy score was very low at approximately only 22%, it does repeatably demonstrate the feature importance for a good predictive nature inherent to the dataset. This demonstration dictates "Salary" as the highest predictor, followed by "Expertise Levels" and ultimately gives us a starting place as an acting framework to build on. 

Unfortunately, there are very clear limitations to the existing data point observations, but this does not entail an inability to become a workable strategy as shown in the visualizations. With the observations given, the aspects related to a "Machine Learning Engineer" as an example, show how we can easily predict a large trend represented for a given timespan that increases in interest as expertise. Proving this is a worthy Job title in the dataset for further study as expertise levels develop even further with time:
![image.png](attachment:image.png)

And here again, we can see how all of the top 4 data Job titles will gain in their expertise level over time, which shows a trend for growing interest and demand in the field of data jobs:
![image-2.png](attachment:image-2.png)

Although the largest challenge is the low accuracy score as related to the nature of the current working dataset, it is believed that as growth in the observations develops over time, so too will the accuracy score from better training data. Therefore, this endeavor is still of worthy pursuit but will require further investments or subsidies before it can provide an admirable accuracy score duplicated by the ML model itself. I would advise assisting in the efficient development of the model through the means of more observations and a decided focus for select Job titles from the open field. The following data frame selects from the highest occurring titles and serves as the proposal for limiting job types to the top 4 given data jobs and respective course programs through universities:
![image-3.png](attachment:image-3.png)


## Future Uses Or Additional Applications, Recommendations, & Implementations With Ethical Assessments

There are several available methods worthy of employing the predictive functions for our model. We could attribute a DTC(Decision Tree Classifier), an ensemble RF(Random Forrest), or even define a multivariate Liner Regression model once adequate collections amass as a worthy set of observations. However, the goal will be to incorporate features that best attribute to a classification prediction for a "Target Job" as the elected Job Types found in the "Data Science Salaries" dataset from Kaggle. Further emphasis on limiting or complimenting desired course programs should also be considered when applying supplemented observations from which to train. 

As for Challenges, finding the best method to produce the highest accuracy for predictions will be limited by the available data point observations until time has amassed a broader working dataset, and the selective features derived from the given dataset should be maintained. However, since this is intended as a framework at current, any additional future subsidy will also escalate the findings to train for a more robust model but also serve as research and improvement metrics during the post and collective interim. The biggest issue will be on how to implement that framework and moderate the functions thereof in an efficient and expedient manner that does not interfere with student motivations.

As of now, there are no known ethical considerations as it is entirely a subjective modus in way of preferences or performance by the given user, and establishes a real-world evolving assessment to best assume the predictive nature of the provided Job types. Assigning these career goals only serves as a start-to-finish customization of educational goals based on the predictive quality of the output. Therefore, they are intended as guidance, but not guarantee. Since there are no guarantees, nor assessment metrics presented on behalf of the users, there are also no permanent nor demonstrative markers issued to the identity of any given user. Thus, due to this subjective preference and the best current assignment for correlative values, no ethical constraints are necessarily considered nor needed. 


All validation of output accuracy will be gained from the chosen method of the model implemented. As for the outcomes, follow-up surveys or retention rate increases of the users within the pool of model participation are excellent means for performance metrics. Having the comparative analysis of projected accumulations accounting for before the model's use vs after could even prove productive or inconclusive. Analyzing other open source datasets, or available updates that complement existing feature markers is another means of supplementing observations, but guidance to relevance should be cautioned in the development.

However, imploring techniques as a motivator for student completion is a valid trade-off for headhunting students to better fit their needs. This will aid in graduation rates and subsequent reputation-building efforts. Also, issuing survey rounds to analyze user content towards efforts employed during and after program attendance, could provide a means for additional improvement metrics or advice. 

As a final note, this survey proposition has no bearing on performance but could be desired for additional marketing or extending research purposes. At Kukis-Garo, we are always looking forward to a better tomorrow where dreams await us, and cooler heads prevail. 

## Appendix

#### Definitions

|TERM              | MEANING                                                       |
|------------------|---------------------------------------------------------------|
|RF                |(Random Forest classifier)                                     |
|DTC               |(TDecision Tree classifier)                                    |
|Size              |(Company Size as large, medium, small)                         |
|Job               |(Job Titles)                                                   |



#### Reference

BANERJEE,SOURAV(2023) "Data Science Salaries", Kaggle.com, https://www.kaggle.com/datasets/iamsouravbanerjee/data-science-salaries-2023



```python

```
