# DSPortfolio

Collection of Data Science projects by Michael Szczepaniak

## Tasty_Bites

### Business problem

Website provides healthy, well-balanced recipes and offer meal plan subscriptions that deliver ingredients so that customers can make them at home. The site is free to use to search recipes. Featured recipes are posted on the home page. If a popular recipe is posted, site traffic increase as much as 40%. Incease in site traffic, increases subscription rates.

At present, there is no well-defined process for selecting a recipe for the home page. It is currently done ad hoc, by the product manager based on what they like. The product manager would like to develop a process that can select high traffic recipes 80% of the time.

### Data

Data is provided in the comma separated variable (CSV) file ***recipe_site_traffic_2212.csv*** which has 4812 rows and 11 columns. The 11 columns are as follows: *recipe, calories, carbohydrate, sugar, protein, category, servings, high_traffic* respectively. Details regarding each variable and how it was preprocessed and used are provided in the project notebook.

### Analysis

After some EDA, a baseline logistic regression model was built and two random forest classifiers were built as comparator models.

## Netflix_Movies

### Business problem

What were the top 3 movie genres since 1990? Is there are significant difference in duration between the top 3 movie genres since 1990?

### Data

Data is provided in the comma separated variable (CSV) file ***netflix_data.csv*** which has 947 rows and 8 columns. The 8 columns are as follows: *show_id, type, title, director, cast, country, date_added, release_year, duration, description, genre* respectively.

### Analysis

After some EDA, a 1-way ANOVA was run between the top 3 genres.

## NYC Public High Schools

### Business problem

TODO

### Data

TODO

### Analysis

TODO

## Nobel Winners

### Business problem

TODO

### Data

TODO

### Analysis

TODO

