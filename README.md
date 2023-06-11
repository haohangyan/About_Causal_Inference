# Project Description
In this repository, we undertake a deep dive into movie ratings data, focusing primarily on exploring potential causal relationships. Using a rich dataset from movie ratings, we address key questions aimed at extracting meaningful insights that could be useful for stakeholders in the movie industry.

# Dataset Description
We use a dataset that comprises ratings data for 400 movies from 1097 research participants. The dataset includes columns representing:

Movie ratings (Columns 1-400)
Self-assessments on sensation seeking behaviors (Columns 401-420)
Responses to personality questions (Columns 421-464)
Self-reported movie experience ratings (Columns 465-474)
Gender identity (Column 475)
Only child status (Column 476)
Preference for watching movies alone or with others (Column 477)
Missing data in the dataset has been handled using appropriate imputation methods.

# Causal Inference Approaches
We employ various statistical and machine learning techniques to infer potential causal relationships, such as:

Regression models (both linear and logistic) to understand the influence of factors such as gender, sibship status, and social viewing preferences on movie ratings.

Hypothesis tests to investigate specific questions about the dataset, such as the influence of movie popularity and age, or the impact of gender and sibship status on ratings of specific movies.

Analysis of the distribution of ratings for specific movies and movie franchises, identifying any inconsistencies in the perceived quality of movies within the same franchise.

# Dependencies
To run the scripts in this repository, the following Python libraries are needed:

numpy
pandas
scipy
statsmodels
sklearn
matplotlib
seaborn
Usage
Clone this repository to your local machine.
Install the necessary dependencies.
Run the scripts in the 'src' directory.
# Results
The results from our analysis are available in the 'results' directory. They include:

Detailed responses to the ten core questions posed by the project
Additional insights derived from exploratory data analysis and hypothesis testing
Visualization plots to aid in understanding the results

# References
Wallisch, P. & Whritner, J.A. (2017). Movie preferences are predictable from personality and gender, but not always.
