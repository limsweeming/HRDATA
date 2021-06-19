#### Human Resource Dataset
Leveraging HR data can help inform and improve the strategies used by HR and that is including recruitment, training and development, compensation and even turnover rates. This chosen HR dataset is specifically focusing on the organization turnover rates and what constitute to the consequences. 
More on the data collected, the organization HR conducted a survey on their employees and the survey is designed carefully to reveal great deal of information about them. For instance, the HR can tell whether the employee would prioritize family versus working hours or job position vs income. Next is to link to their job satisfaction and here come the main question: are they still working for the company?
In this sense, the researcher can potentially evaluate employee’s decision to leave or stay in the company with a predictive model. Further emphasis, the aim of this project is not based on subjective point of view where HR would think “the employee left because the job is not good” but on an objective insights which is reflecting on employee’s opinion and their job experience.

#### Features Description
Exploring the dataset, there are a total of 35 columns and close to 1500 rows. The number of columns are consider good which could open up to a lot of possible analysis. The dataset contains employee’s background and work-related activities. 

#### Project Brief and Problem Statement
An organization with a bad turnover rate is costly and is affecting the productivity. This is a severe situation where every manager’s nightmares to see employees resigning because of the loss of valuable knowledge and experience. On the other hand, HR would experience the frustration to find a suitable replacement every time which involves time, money and risk. 
The approach here is to develop a predictive model to predict who will be likely to resign. This allows HR to act quicker to retain the employee rather than to find out the reason after the exit interview. That will be too late!
In addition, the researcher hopes to identify better retention employee strategies through the data so that the HR can consider to adopt. 

#### Predictive Model Workflow
* Data Pre-Processing – Handle missing valuesremove variables, bin variables such as the job satisfaction level. Detect the outliers which is the odd one out and identify them. 
* Early Data Analysis – Identify 2 groups of employees who stay or had resign. To better understand both group decisions of whether is because of income, working hours, etc
* Model Training – Supervised training. Manage imbalance dataset (80% test and 20% accuracy). Using N Naïve Bayes, k-nearest neighbors algorithm and random forest to train and text. Objective here is to form 3 themes to train such as old age, overtime and salary or all three combinations. 
* Model Validation – Using K-Fold/Confusion Metric techniques to validate how good is the model 
* Model Predictions – After the best model selected, generate the outcome and do tuning to the best interest of the results
* Conclusion and recommendation – Focus on which employees are leaving and why. 

