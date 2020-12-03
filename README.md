# Michigan Python 12/3/2020

### MAIN TOPIC BRIEF:
Is there a significant relationship between US Covid-19 mortality, age, race, and primary spoken language? What is the impact of 2020’s pandemic on healthcare accessibility? These questions can be answered using Python to extract, visualize and analyze data. This talk features a team of students’ journey in data analysis using Python and R to determine predictors of Covid-19 mortality and the pandemic’s effect on accessibility to healthcare across a variety of demographics.

### Regression Analysis
"The fundamental premise of data modeling is to make explicit the relationship between: 
an outcome variable y, also called a dependent variable or response variable,
and
an explanatory/predictor variable x, also called an independent variable or covariate"

Two variables can be said to have a linear relationship if, when plotted, these points appear to move in a straight line.

Correlation coefficients calculate a numerical value to describe the strength of the relationship between variables 
![correlation coefficient matrix](https://d33wubrfki0l68.cloudfront.net/860c9756c9d4b158ab4a29a33bc919729be9d92b/9823b/moderndive_files/figure-html/correlation1-1.png)

By modeling this relationship, one can make predictions based on the trends existing in the variables.

It is important to analyze the strength of the model created, to ensure this model 'best fits' the original data.

### Linear Regression Example

"AmazonBooksExample.py"
data: https://www.kaggle.com/sootersaalu/amazon-top-50-bestselling-books-2009-2019 

### Covid-19 Data Analysis

About Stanford's Blueprint Datathon

"Blueprint Datathon is a competition at Stanford, hosted by Stanford Health Innovations for Future Technologies (SHIFT). We bring together students from diverse backgrounds to apply big data analytics to challenges in healthcare.

We encourage undergraduate and graduate students with interests in Healthcare, Computer Science, Economics, Mathematics, or Business to participate. Participants will be provided with a few cases and corresponding data sets covering a health/biotech problem studied by industry and academia to discover meaningful insights.

We expect participants to use statistical analysis techniques and tools to explore the data provided, and use the insights to make recommendations and qualitative models for adoption by appropriate stakeholders."

https://www.blueprintdatathon.com/

**Blueprint Datathon 2020 submission:** https://devpost.com/software/blueprint-datathon#updates

Vertical 2: Health Disparities and infrastructure

"The pandemic has highlighted the long-standing disparities and inequities that exist in the health infrastructures of many countries around the world, including in the United States. Issues such as lack of access to quality health facilities, socioeconomic conditions, and racial discrimination disproportionately affect vulnerable and marginalized populations. 

Your task will be to analyze given data to identify key socioeconomic factors that are contributing to these disparities, and understand how these disparities themselves progress as the pandemic continues."


**Blueprint Datathon 2020 github repo:** https://github.com/s-ryanlee/BlueprintDatathon

### Resources

Modern Dive, Chapter 5: Basic Regression https://moderndive.com/5-regression.html

Blueprint Datathon Pandas, Data Visualization, and Sklearn Overviews

