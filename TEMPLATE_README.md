# Movie Revenue Analysis:Maximizing Profitability and Audience Satisfaction

**Authors**: Celestine A. Imelda

## Overview
Three datasets—bom.movie_gross.csv, title.basics.csv, and title.ratings.csv—will be analyzed as part of the project named "Exploring Movie Gross Earnings, Ratings, and Genre Trends" in order to get insights. The focus of the examination will be on the financial performance of films and how much money they made overall. The research will also examine movie ratings, taking into account both audience and critic ratings, in order to comprehend how public perception and financial success are related. In addition, a study of film genres will be done to spot trends and patterns and discover which genres tend to succeed in the constantly changing film industry. The initiative aims to deepen our understanding of the elements that influence success in the film industry by offering insightful information about the relationships between movie earnings, ratings, and genre preferences.

## Business Problem

This data analysis project aims to optimize movie-making decisions and marketing strategies for a production company by maximizing profitability and audience satisfaction. Insights from the data will guide decision-making, aligning with company objectives and minimizing investment risks.

## Data
This project's data is derived from three datasets: bom.movie_gross.csv, title.akas.csv, and title.ratings.csv.

This dataset, bom.movie_gross.csv, which will help with revenue creation, comprises data on movie titles and their accompanying domestic and international gross revenues.

This file, title.akas.csv, lists alternative movie names and details on regional release. Understanding regional preferences in movie titles and how regional titles affect movie revenue and popularity is crucial.

IMDb ratings and the total number of votes for each movie are included in the file known as title.ratings.csv. It is essential for examining the relationship between IMDb ratings, audience satisfaction, and box office receipts.

Sample and Data Representation

The information in the statistics pertains to numerous movie releases and their performance indicators.


## Methods

The approach of conducting descriptive analysis is appropriate given the data and the business problem because it provides an initial understanding of the dataset's characteristics, uncovers patterns, and informs subsequent steps of the analysis. Descriptive analysis is essential for identifying potential trends and factors influencing movie success, guiding further modeling or in-depth analysis in later phases. It helps the production company make informed decisions and prioritize their efforts to achieve the desired goals of maximizing profitability and audience satisfaction, the use of box plots, graphs and heat map have also helped with an easier understanding of the data.

## Results

The descriptive analysis offers valuable insights into the key factors affecting movie success, including genre preferences, release years, production budgets, and regional adaptations. These findings can serve as a basis for data-driven decision-making to optimize movie production and marketing strategies. However, it is crucial to acknowledge that the results may not fully generalize beyond the current dataset

### Visual 1
![graph1](./images/viz1.png)

## Conclusions

Based on the analysis performed, I recommend the business to focus on producing movies that align with popular genres and have a track record of higher audience satisfaction and revenue. The findings highlight the importance of investing in movies with larger production budgets, as they tend to perform better financially. 

Limitations and Next Steps:

The analysis's scope is limited, and results may not fully solve the business problem. Validation with external data and causal analysis is needed.
Unexplored factors like marketing strategies and audience segmentation could enhance insights.
Future work may involve predictive modeling, audience segmentation, and longitudinal analysis to improve decision-making and stay competitive in the industry.


## For More Information

Please review our full analysis in [our Jupyter Notebook](./dsc-phase1-project-template.ipynb) or our [presentation](./DS_Project_Presentation.pdf).

For any additional questions, please contact **name & email, name & email**

## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── __init__.py                         <- .py file that signals to python these folders contain packages
├── README.md                           <- The top-level README for reviewers of this project
├── dsc-phase1-project-template.ipynb   <- Narrative documentation of analysis in Jupyter notebook
├── DS_Project_Presentation.pdf         <- PDF version of project presentation
├── code
│   ├── __init__.py                     <- .py file that signals to python these folders contain packages
│   ├── visualizations.py               <- .py script to create finalized versions of visuals for project
│   ├── data_preparation.py             <- .py script used to pre-process and clean data
│   └── eda_notebook.ipynb              <- Notebook containing data exploration
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code
```
