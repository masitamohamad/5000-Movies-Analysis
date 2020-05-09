# Project Proposal - Can we predict the success of a movie?

For this project, we are hoping to discover what factors create popular movies. We want to achieve this by answering questions based on our combined interests in the dataset.

Let's explore and ask the data what information it holds.

## Overview

In this repository we will store all relevant project documents. We will use Jupyter Notebooks for processing, clean up, analyzing and visualizations. We found the 5000-movie database and according to TMDB the “movies are query-able by fields like average rating, certifications, release dates and genres.” Other categories such as spoken language, popularity, and title will help us to identify the data and answer our questions.

Sources utilized for data, articles, and topic research:

* https://www.kaggle.com/tmdb/tmdb-movie-metadata
* https://www.themoviedb.org/documentation/api
* https://github.com/datadesk/cpi

## Workflow

We will divide the workflow so as to fairly distribute the work between team members. We start by assigning the main task of coding the data cleanse to one person as the group participates in research and troubleshooting. We then divide up our brainstormed questions and each member has at least one question to answer (depending on other task assignments like cleaning data and managing project documents on GitHub). By using the skills we have learned to date we will compare various characteristics that make a movie popular and hopefully create a set of conclusions and variables to predict the success of a movie.

#### Para-Project Tasks:

* Data Wrangling : Ally
* GitHub : Anastasia

#### Discovery Questions:

* Can we predict the success of a movie? - Team
* What’s the trend between decades and movie genre? -Grace
* Comparison of popularity by geography? - Anastasia
* How does budget correlate with popularity? - Kellie
* Linear regression on popularity in production cost? - Masita
* Decades and blockbuster success: Is it cyclical? Is there genre resurgence? - Kellie
* Correlation between runtime and popularity? - Grace
* Relationship between genre and rating? - Masita
* Correlation between the length of titles and voter rating? - Ally

## Data File

* tmdb_5000_movies.csv (original downloaded data from Kaggle)

### Jupyter Notebooks

* *Project1_DataCleaning.4.19.2020.aq* for processing and cleaning up ".csv" raw data: Ally with team participation
  * Export to a new ".csv" file for further team analysis (*clean_movie_df_aq.csv*)

* *Project1DataAnalysis_AQ.ipynb*: Ally
  * **Can we determine what was popular by length of title and voter rating?**

* *AValdes_Project1.ipynb*: Anastasia
  * **Can we determine what was popular by geography?**

* *Cox_Project_1.ipynb*: Kellie
  * **Can we determine what was popular by decade? Was there any genre resurgence?**

* *GHuefner_Work.ipynb*: Grace
  * **What's the relationship between runtime and pepularity?**

* *MMohamad_Project1.ipynb*: Masita
  * **Can we determine what was popular by production budget or genre?**

## Project Team Presentation

* File name : *Project_1_Presentation_Movie_Success.pdf*
* Overview of project ideas, teammembers, agenda
* Summary of results from all analyses performed, including data visualization
* Conclusions, Challenges and Ideas for more future in-depth analyses