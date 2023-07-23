# MICROSOFT MOVIE STUDIO ANALYSIS

Author: John ELvis

## Overview 
This project employs exploratory data analysis to extract valuable information for Microsoft, aiming to establish a new movie studio. By analyzing datasets from IMDB and Box Office Mojo, the project provides recommendations regarding the film genres that Microsoft should consider exploring. 

The success and popularity of each genre are evaluated using two key metrics: the total gross incomes and the critical response. The results suggest that Microsoft would benefit from concentrating on genres such as Sci-Fi, adventure, animation, and action, as these genres have demonstrated higher total gross income.

## Business Problem

Microsoft intends to join the league of prominent companies by venturing into the production of unique video content. To accomplish this, they plan to establish a movie studio. However, their lack of expertise in the field poses a challenge. This analysis primarily focuses on examining the prevailing trends in successful movies at the box office. Through an exploratory data analysis, valuable insights are generated, which can be used by the head of Microsoft's new movie studio to make informed decisions regarding the genres and themes of films to produce.

Questions :<br>
Which genre of movies have the highest gross income?<br>
Which genre of movies have a higher average rating?<br>
What is the relationship between the average rating and the gross income?<br>
What is the domestic gross and foreign gross income by start year of the movies?<br>

## Data

The datasets utilized for this analysis are sourced from IMDB and Box Office Mojo. The following is a brief overview of the three datasets:
- imdb.title.basics: Contains info about movie titles such as primary title, original title, start year, runtime minutes  and genres.
- imdb.title.ratings: Contains the IMDb rating and votes information for titles.
- bom.movie_gross: Contains the domestic gross and foreign gross for the movie titles.

## Methods
This project employs exploratory descriptive analysis using several essential steps to gain valuable insights. The process involves importing necessary libraries and loading the datasets, understanding the data, performing data cleaning, and finally, visualizing the data for a comprehensive exploration.

## Results
Among the genres present in this dataset, drama, comedy, and action stand out with the highest number of movie releases. Drama and comedy likely hold the title of the most extensive film genres due to their inclusivity of a wide range of films.
![My image](images\Number_of_movies_per_genre.png)

The difference between the heights of the bars, which represent the average rating, is quite small.Documentary, biography and sport have the highest average rating while family, thriller and horror have the lowest average rating.
![My image](images/rating_by_genre.png)

Box office Mojo tracks theatrical box office earnings. The genres with the highest income are Sci-Fi, adventure, animation and action while the genres with the lowest income are romance, documentary and war.
![My image](images/income_by_genre.png)


There is no clear relationship between the total gross income and the average rating. However, movies with a low average rating of below 4 have a low total gross income.
![My image](images/gross_vs_rating.png)


Throughout the years, the foreign gross is often higher than the domestic gross income when a movie is released. Movies that were released in 2018 had the highest foreign gross and domestic gross income.The gross incomes then drastically dropped to their lowest for movies that were released in 2019. 
![My image](images/start_year.png)



## Conclusions and recommendations
- Documentary, biography and sport have the highest average rating while Sci-Fi, adventure, animation and action have the highest total gross income.Despite documentary and biography having the highest average rating, they have a very low income.There is no clear relationship between the total gross income and the average rating.
- Microsoft should consider focusing on genres with the highest total gross income in order to get higher returns on their investment. These genres are Sci-Fi, adventure, animation and action.
- Microsoft should focus on exploring more the international markets which have had a higher gross over the years when compared to the domestic markets. The movies created should consider the interests of the international market.
- Due to the drastic drop in the gross from theatrical earnings for movies released in 2019, Microsoft should look into other sources of revenue and invest in them.

## Future work
- Further research should be done to determine the best time of the year to release a movie of a certain genre.
- It is beneficial to determine whether the total gross income of a genre increases proportionally if the production, development, marketing, and advertising budgets of the movie are increased. This can help in predicting the profits based on the budget.
- Other than theatrical earnings, there are other sources of revenue for studios such as home entertainment sales and rentals, television rights, product placement fees and streaming services. It would be important to collect data about these sources of revenue and compare them to the revenue from the theatre earnings.



## Repository Structure
├── images                                         <- Both sourced externally and generated from code <br>
├── zippedData                                     <- Both sourced externally and generated from code <br>
├── README.md                                      <- The top-level README for reviewers of this project <br>
├── presentation.pdf                               <- PDF version of project presentation <br>
└── student.ipynb                                  <- Narrative documentation of analysis in Jupyter notebook <br>