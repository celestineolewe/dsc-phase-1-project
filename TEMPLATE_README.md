# Movie Revenue Analysis:Maximizing Profitability and Audience Satisfaction

**Authors**: Celestine A. Imelda

## Overview

This project aims to analyze three datasets: "bom.movie_gross.csv," "title.akas.csv," and "title.ratings.csv." Its goal is to assist a movie production company in making optimized movie decisions and effective marketing strategies. By handling missing values, standardizing titles, and merging relevant data, the project seeks to identify patterns and relationships between movie revenue, ratings, and other factors. By providing actionable recommendations based on the analysis, the movie production company can enhance movie quality, target specific markets, and improve financial success and audience satisfaction in a competitive film industry.

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

The approach of conducting descriptive analysis is appropriate given the data and the business problem because it provides an initial understanding of the dataset's characteristics, uncovers patterns, and informs subsequent steps of the analysis. Descriptive analysis is essential for identifying potential trends and factors influencing movie success, guiding further modeling or in-depth analysis in later phases. It helps the production company make informed decisions and prioritize their efforts to achieve the desired goals of maximizing profitability and audience satisfaction.

## Results

Interpretation of Results:
The descriptive analysis provides valuable insights into the factors impacting movie success. It highlights the importance of movie genres, release years, production budgets, and regional adaptations in achieving higher revenue and audience satisfaction. Understanding these patterns can aid in making data-driven decisions to optimize movie-making strategies and marketing efforts.

Generalization of Results:
While the descriptive analysis provides valuable insights from the current dataset, it is essential to acknowledge that these findings may not fully generalize beyond this specific data. Factors influencing movie success can be dynamic and subject to change over time and across different contexts. Further analysis and validation with additional datasets and external sources would enhance the confidence and broader applicability of the results.
Here is an example of how to embed images from your sub-folder:

### Visual 1
![graph1](./images/viz1.png)

## Conclusions

Conclusions:

The descriptive analysis provides valuable insights for the movie production company. Recommendations include focusing on successful genres, strategic release planning, optimizing budget allocation, and tailoring marketing strategies to regional preferences.

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
