## Econometrics 2023-2024

[Link](https://docs.google.com/spreadsheets/d/1RQleL7JTMyd15bdXAbWV4RfzFBIhEh3BL9bn1CL43LI/edit?usp=sharing) for spreadsheet with activity

 - 1 point for participation in discussion
 - 2 points for solving a task at the whiteboard


[Link](https://docs.google.com/spreadsheets/d/1w-plim5Lwl-xjx0S3Kh0yI_2acUW9aQCvlVJmPBnhXs/edit) with the grades for Quizes and Exams

## Work in R

- DataCamp R Courses

  - [Introduction to R](https://www.datacamp.com/courses/free-introduction-to-r)
  - [Intermediate R](https://www.datacamp.com/courses/intermediate-r)
  - [Introduction to Regression in R](https://www.datacamp.com/courses/introduction-to-regression-in-r)
  - [Intermediate Regression in R](https://www.datacamp.com/courses/intermediate-regression-in-r)

- [Google Colab](https://colab.research.google.com/notebook#create=true&language=r) with R  

- [R kernel for Jupyter](https://github.com/IRkernel/IRkernel)


## Recommended literature:

1) Dougherty. Introduction to Econometrics

+ Teaching book recommended by UoL. 
+ Has Study guide with tasks similar to UoL exam.
- More words than formulas + inconvenient notations. 

2)  Картаев. Дружелюбная эконометрика (https://books.econ.msu.ru/Introduction-to-Econometrics/)

+ Best teaching book to understand the basics. A lot of intuitive explanations and helpful tasks

3) William H. Greene. Econometric Analysis

+ Great book with clear proofs in matrix form

4)  Stock, Watson. Introduction to Econometrics

+ Has a section with needed topics from Mathematical statistics. Has both matrix and normal notations.




## Instructions for Project N1

Dear students, you are about to complete you Project N1. We present to you the instructions on how to proceed with it.

1. The homework is to be done in mini-groups of 2-3 people (if necessary and with a strong desire, the work can be done independently). Mini-groups can only consist of students assigned to one seminar teacher!

2. You need to conduct an econometric study. To do this, find data on the topic of interest to you that meet the following requirements:
• The data should belong to the cross-sectional type (not panel or time series)
• Based on the data, it should be possible to build a multiple linear regression (i.e., the data should include a variable whose behavior can at least hypothetically be explained by other variables in the data)
• The number of observations: from 50 to 1000 (the lower bound is strict, the upper is not)
• The number of variables: at least 5 independent variables, with at least one dummy variable included

Possible data sources: Kaggle, the Rosstat website, World Bank, OECD and other international organizations websites. You can also use the data you used elsewhere or manually collect data from any website (you can use a web scraping program).

Example: how the education influences the income of a person?
The data was obtained from RLMS survey.
Variables:
o dependent variable: income of a person
o independent variables: person’s education (the main variable we are interested in in out project) and a set of control variables: age, marital status, profession etc. 

3. After you have chosen the data, you need to enter the data source (as well as information about the selected time period and variables for work, and about your team) into a Google spreadsheet: 

https://docs.google.com/spreadsheets/d/1EBYAMJosp290_7xnD1TZItUaXC3fnHU4jOjsE4WI4dU/edit?usp=sharing 

Before adding your data to the table, please make sure that your classmates are not using the same data, otherwise the grade for the work of both groups using the same data will be 0.

The deadline for entering information about groups, data, and variables is November 21 at 23:59.

4. You have chosen the data, entered the information about it into the table, and now you can proceed directly to the econometric research!

**The deadline** for submitting the homework is December 10 at 23:59. Starting from 00:00 on December 11, the work is penalized by 1 point; for each subsequent hour of delay, an additional 1 point will be deducted.


### How to submit?

One member of the team should 

1. Follow  the invitation link for your homework (https://classroom.github.com/a/3kfQF7nm).
2. Log in to GitHub. You will be presented with a list of students.
3. Find yourself on the list and follow the further instructions. A personal team repository will be automatically created for you. 

Warning: if you do not find yourself in the list of students, please DO NOT proceed with the ‘Can't find your name? Go to next step ->’. Instead, write to your class teacher. We will add you to the list, after which you can continue with step 3. If you follow the link, then the repo can still be created, however, it will not be connected to the Classroom, which will lead to some inconveniences in the future. If you’ve clicked on the link ‘Can't find your name? Go to the next step ->’ and only then saw this warning: still write to your class teacher or teaching assistant about this. Connecting isolated cases is easier.

Before the deadline  you should add the following three separate files to your team repo:

1) The text of the work in PDF format. The main plots and tables should be included in the text of the work.
2) Code (in any software).
3) Data.


### What to submit?

Your project text may contain the following sections (this structure is not mandatory, you can use any other you like) and the approximate grading for each part:

1)  Introduction (3 points)

  - (2 point) Introduce problem (Specify what is the variable of interest? what is the goal of the research?) 
  - (1 point) Review of the relevant scientific literature

2)  Data description: source, tables, plots (3 points) 

  - Describe data source 
  - Present only  those  results which are important for model estimation (e.g. present box-plots if you have outliers, if you suspect non-linearity present scatter plots and (optionally) transform variables, etc.). Don't forget you have to comment on each plot/table included in your report. 

3)  Economic model (3 points total)

  - Give comment about the choice of functional form (linear? log? polinomial?) based on theoretical and common knowledge 
  - Do you have omitted variables? Do you have excessive variables?
  - Hypothesize how your explanatory variables should influence your dependent variable
  

4)  Model estimation results (3 points)

  - Interpret the estimated coefficients (do not forget what is meant by economic interpretation)
  - Does the obtained effect size/effect direction coincide with you hypotheses?

5)  Discussion (2 points)

  - Sum up obtained results. If you have obtained questionable results think about the reasons (problems with data, problems with specification, violations of GMT)
  - Suggest ways to improve your model
  


Final comments:

Your report should be 3-10 pages long. The main idea -- you should cover all the points above, but be brief and precise. 


