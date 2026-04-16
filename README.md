# DSPortfolio

Collection of Data Science projects by Michael Szczepaniak

## Tasty_Bites

This was the DS601 project completed as part of my [Data Scientist certification through DataCamp completed in March 2026.](https://www.datacamp.com/certificate/DS0029339021283)

### Business scenario and challenge

This business has build a website which provides healthy, well-balanced recipes and offer meal plan subscriptions that deliver ingredients so that customers can make them at home. The site is free to use to search recipes. Featured recipes are posted on the home page. If a popular recipe is posted, site traffic increase as much as 40%. Incease in site traffic, increases subscription rates.

This project addressed the challenge that there was no well-defined process for selecting a recipe for the home page. It was done ad hoc, by the product manager based on what they like. The required a process well-defined process that could select high traffic recipes 80% of the time or better.

### Data

Data is provided in the comma separated variable (CSV) file ***recipe_site_traffic.csv*** which has 4812 rows and 11 columns. The 11 columns are as follows: *recipe, calories, carbohydrate, sugar, protein, category, servings, high_traffic* respectively. Details regarding each variable and how it was preprocessed and used are provided in the project notebook.

### Analysis highlights

After some EDA, a baseline logistic regression model was built and two random forest classifiers were built as comparator models. The more performant model was used as part of the new process for selecting recipes that users would see on the home page.

## Netflix_Movies

This project had two parts. The first part explored top movie genres since 1990.

### Business questions and tasks

Part 1. - What were the top 3 movie genres since 1990? Is there are significant difference in duration between the top 3 movie genres since 1990?

Part 2. - What is the impact of each feature on rental duration? Build models to predict movie rental durations from existing features.

### Data

Part 1. - Data is provided in the comma separated variable (CSV) file ***netflix_data.csv*** which has 947 rows and 8 columns. Detailed descriptions of each column are provided in the ***NetflixGenreEda.ipynb***

Part 2. - Data is provided in the comma separated variable (CSV) file ***rental_info.csv*** which has 15861 rows and 15 columns. Detailed descriptions of each column are provided in the ***PredictingMovieRentals.ipynb***

### Analysis

Part 1. - After some EDA, a 1-way ANOVA was run between the top 3 genres.

Part 2. - Investigate impact features on length of rental, build build and compare models that predict rental length (regressors), build and compare models that predict whether a rental will be late (binary classification)

## NYC Public High Schools

### Research questions

1. How do SAT scores distribute across the 5 boroughs?
2. Are any of the differences in median scores significant?
3. Which schools are the best in math?


### Data

Data is provided in the comma separated variable (CSV) file ***schools.csv*** which has 375 rows and 7 columns. The 11 columns are as follows: *school_name, borough, building_code, average_math, average_reading, average_writing, percent_tested*. There are no missing values in the first 6 columns. In the *percent_tested* column, 20 values were missing.

### Analysis

Visualization comparing SAT distributions of each borough, KW tests of pairs to determine significant, visualization of top math schools

## Nobel Winners

### Research questions

+ How does sex and country of birth influence the distribution of Nobel prizes?
+ How has the proportion of men and women receiving Nobel prizes changed over time?
+ What do the age distributions of men and women look over the Nobel prize categories?

### Data

The original data can be found at:
https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/JA5QBC
A subset of this data was used for this analysis

### Analysis

There were not models built in this project, but alot of data wrangling was done to create many interesting graphics.

## LA Crime

### Research questions

1. Which hour has the highest frequency of crimes?
2. What types of crimes occur during the most frequent hour?
3. Which areas have the highest and lowest frequency of night crimes?
4. How do crimes committed against victims distribute accross different age groups?

### Data

The data for this project was extracted and modified from the Los Angeles - Open Data Portal
https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-2024/2nrs-mtv8/about_data

### Analysis

There were not models built in this project, but alot of data wrangling was done to create several interesting graphics.

## Prepare_Data_for_Modeling

### Business scenario and challenge

A common problem when creating models to generate business value from data is that the datasets can be so large that it can take days for the model to generate predictions. Ensuring that the dataset is stored as efficiently as possible is crucial for allowing these models to run on a more reasonable timescale without having to reduce the size of the dataset.

In this scenario, we are asked by a training provider called *Training Data Ltd.* to clean up one of their largest customer datasets. This dataset will eventually be used to predict whether their students are looking for a new job or not, information that they will then use to direct them to prospective recruiters.


### Data

Data is provided in the comma separated variable (CSV) file ***customer_train.csv*** which has 19158 rows and 14 columns. The 14 columns are as follows: *student_id, city, city_development_index, gender, relevant_experience, enrolled_university, education_level, major_discipline, experience, company_size, company_type, last_new_job, training_hours, job_change*

### Analysis

TODO

## Airbnb_Market_Trends

### Business scenario and challenge

TODO


### Data

TODO

### Analysis

TODO

## Car_Insurance_Outcomes

### Business scenario and challenge

Identify the single feature that results in the best performing model which predicts whether a driver will make a claim.


### Data

Data is provided in the comma separated variable (CSV) file ***car_insurance.csv*** which has 10000 rows and 18 columns. The 14 columns are as follows: *id, age, gender, driving_experience, education, income, credit_score, vehicle_ownership, vehicle_year, married, children, postal_code, annual_mileage, vehicle_type, speeding_violations, duis, past_accidents, outcome*

### Analysis

TODO

## Hypothesis_Soccer

### Business scenario and challenge

Is there a significant difference in the number of goals scored in FIFA World Cup women's versus men's matches?


### Data

Men data: https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017

Women data: https://www.kaggle.com/datasets/piterfm/football-fifa-womens-world-cup-1991-2023

### Analysis

Data wrangling focused on filtering for only FIFA world cup matches followed by testing the following null and alternative hypotheses:

$$H_0$$: The mean number of goals scored in women's international soccer matches is the same as men's.

$$H_A$$: The mean number of goals scored in women's international soccer matches is greater than men's.

## Predictive_Ag_Modeling

### Business scenario and challenge

In this project, a multi-class classification models to predict the type of "crop" and identify the single most importance feature for predictive performance is built.


### Data

The dataset has 2200 rows and the follow 5 columns:

"N": Nitrogen content ratio in the soil
"P": Phosphorous content ratio in the soil
"K": Potassium content ratio in the soil
"pH" value of the soil
"crop": categorical values that contain various crops (target variable).

Source: TODO

### Analysis

After doing some EDA done on each independent variable, single predictor logistic regression models were built with each independent variable to identify the best single predictor. The logistic regression results were validated by repeating this process, but building LDA (linear discriminant analysis) models.

## <project name>

### Business scenario and challenge

TODO


### Data

TODO

### Analysis

TODO