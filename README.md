# Survival-analysis-with-Lifelines-for-Python
This project is a survival analysis performed on a Kaggle dataset, about turnover employees in Russian/ukrainian companies.

Following analyses were performed:
* Kaplan_Meyer survival estimator to model survival in function with time, with a median survival time and confidence intervals.
* Non parametric logrank tests to compare survival distribution between groups
* Cox proportional hazard model to model risk of quitting the company

## Abstract
Employee attrition is defined as the process by which employees leave a company for different possible reasons. We used a Kaggle dataset based on a Russian/Ukrainian worker population to study this phenomenon. Our goal was to determine and quantify the effect of context (industry, profession) and of other aspects (age, gender, wages, means of locomotion, personality traits…) of an employee on his or her chance of quitting a company. To identify the factors which statistically influence the most the attrition, we performed a variable selection using Cox proportional hazard regression based on AIC criterion. We then focused on these main factors by plotting their survival curves using the Kaplan-Meyer estimator, and by comparing distributions of different groups within categorical variables using logrank tests. Industry sector, profession, age, self-control, way of locomotion and wages appeared as the most significant influencing factors, pointing out an increase in chance of quitting a company with increasing age, decreasing self-control, illegal framework of the job, moving by bus, or for some profession or industry categories. Results and their limits regarding the sampling procedure were discussed to draw some general trends and to provide some advice for recruitment procedures.

## Dataset
Data set on employee turnover was found on Kaggle: https://www.kaggle.com/davinwijaya/employee-turnover


## Technologies & languages 
The study was conducted using Python 3.7 with following Libraries
* [Lifelines](https://lifelines.readthedocs.io/en/latest/index.html) - Python library specialized in survival analysis
* [Pandas]
* [Numpy]
