# DSPortfolio

Collection of Data Science projects by Michael Szczepaniak

## Tasty_Bites

This was the DS601 project completed as part of my (Data Scientist certification through DataCamp completed in March 2026.)[https://www.datacamp.com/certificate/DS0029339021283]

### Business scenario and challenge

This business has build a website which provides healthy, well-balanced recipes and offer meal plan subscriptions that deliver ingredients so that customers can make them at home. The site is free to use to search recipes. Featured recipes are posted on the home page. If a popular recipe is posted, site traffic increase as much as 40%. Incease in site traffic, increases subscription rates.

This project addressed the challenge that there was no well-defined process for selecting a recipe for the home page. It was done ad hoc, by the product manager based on what they like. The required a process well-defined process that could select high traffic recipes 80% of the time or better.

### Data

Data is provided in the comma separated variable (CSV) file ***recipe_site_traffic_2212.csv*** which has 4812 rows and 11 columns. The 11 columns are as follows: *recipe, calories, carbohydrate, sugar, protein, category, servings, high_traffic* respectively. Details regarding each variable and how it was preprocessed and used are provided in the project notebook.

### Analysis highlights

After some EDA, a baseline logistic regression model was built and two random forest classifiers were built as comparator models. The more performant model was used as part of the new process for selecting recipes that users would see on the home page.

## Netflix_Movies

This project had two parts. The first part explored top movie genres since 1990.

### Business scenario and challenge

Part 1. - What were the top 3 movie genres since 1990? Is there are significant difference in duration between the top 3 movie genres since 1990?

Part 2. - Predicting movie rental durations (TODO)

### Data

Part 1. - Data is provided in the comma separated variable (CSV) file ***netflix_data.csv*** which has 947 rows and 8 columns. The 8 columns are as follows: *show_id, type, title, director, cast, country, date_added, release_year, duration, description, genre* respectively.

Part 2. - TODO

### Analysis

Part 1. - After some EDA, a 1-way ANOVA was run between the top 3 genres.

Part 2. - TODO

## NYC Public High Schools

### Business scenario and challenge

This project focused on answering 3 questions:

1. How do SAT scores distribute across the boroughs?
2. Are any of the differences in median scores significant?
3. Which schools are the best in math?


### Data

Data is provided in the comma separated variable (CSV) file ***schools.csv*** which has 375 rows and 7 columns. The 11 columns are as follows: *school_name, borough, building_code, average_math, average_reading, average_writing, percent_tested*. There are no missing values in the first 6 columns. In the *percent_tested* column, 20 values were missing.

### Analysis

TODO

## Nobel Winners

### Business problem or motivation

TODO

### Data

TODO

### Analysis

TODO

## LA Crime

### Business problem or motivation

TODO

### Data

TODO

### Analysis

TODO