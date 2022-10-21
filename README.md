# Lead-Scoring_CASE-STUDY-Logistic-Regression

## Problem Statement -

An education company named X Education sells online courses to industry professionals. On any given day, many professionals who are interested in the courses land 
on their website and browse for courses. 
The company markets its courses on several websites and search engines like Google. Once these people land on the website, they might browse the courses or fill up 
a form for the course or watch some videos. When these people fill up a form providing their email address or phone number, they are classified to be a lead. Moreover,
the company also gets leads through past referrals. Once these leads are acquired, employees from the sales team start making calls, writing emails, etc.

X Education gets a lot of leads, its lead conversion rate is very poor. For example, if, say, they acquire 100 leads in a day, only about 30 of them are converted. 
To make this process more efficient, the company wishes to identify the most potential leads, also known as ‘Hot Leads’. If they successfully identify this set of 
leads, the lead conversion rate should go up as the sales team will now be focusing more on communicating with the potential leads rather than making calls to everyone.

The company requires you to build a model wherein you need to assign a lead score to each of the leads such that the customers with higher lead score have a higher
conversion chance and the customers with lower lead score have a lower conversion chance. The CEO, in particular, has given a ballpark of the target lead conversion 
rate to be around 80%.

## Goal of Case Study -

1.  Build a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads. A higher
score would mean that the lead is hot, i.e. is most likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted.

2.  There are some more problems presented by the company which your model should be able to adjust to if the company's requirement changes in the future so you will 
need to handle these as well. These problems are provided in a separate doc file. Please fill it based on the logistic regression model you got in the first step. 
Also, make sure you include this in your final PPT where you'll make recommendations.

## Data -

We have been provided with a leads dataset from the past with around 9000 data points. This dataset consists of various attributes such as Lead Source, Total Time 
Spent on Website, Total Visits, Last Activity, etc. which may or may not be useful in ultimately deciding whether a lead will be converted or not. The target variable,
in this case, is the column ‘Converted’ which tells whether a past lead was converted or not wherein 1 means it was converted and 0 means it wasn’t converted. 

Another thing that you also need to check out for are the levels present in the categorical variables. Many of the categorical variables have a level called 
'Select' which needs to be handled because it is as good as a null value 

## Steps taken to Solve and Build Model -

- Reading Data (Data Inspection)
- Data Cleaning, Manipulation, Treatment & Outlier Analysis
- EDA (Exploratory Data Analysis)
- Data Preparation
- Creating Dummy(One hot encoding)
- Splitting data into Train and Test set
- Feature Scaling
- Building Models
- Making Predictions
- Model Evaluations
- ROC Curve
- Prediction on test set
- Precision- Recall Trade off
- Statical Analysis
- Feature Importance Determination
- Hot Leads Determination
- Conclusion & Recommendations

## Submission details - Files related to Projects 

- Lead Scoring DSC43 GurpreetK_ShivamS : The python file showing coding and data analysis
- Subjective Questions Lead Scoring_GurpreetK_ShivamS : Subjective Questions answers
- PPT LEAD SCORING GURPREETK_SHIVAMS : Final Presentation
- SUMMARY LEAD SCORING GURPREETK_SHIVAMS : Summary on what's done in the entire Project

