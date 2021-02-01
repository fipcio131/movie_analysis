# Movie Industry Analysis

## Problems and questions to be answered:

* What are the industry trends, market size and global gross profits?
* Profitability analysis
* Who are the major players and their best products?
* What genres and specific titles are the best rated?
* What is the mean return of investment?
* What is the most efficent production budget size and genre?
* How can you get the biggest investment return? What kinf of movie Microsoft should produce?


## Databases used in the analysis

Databases used in the analysis are included in zippedData folder and listed below:
* tn.movie_budgets.csv.gz
* tmdb.movies.csv.gz
* rt.reviews.tsv.gz
* rt.movie_info.tsv.gz
* imdb.title.ratings.csv.gz
* imdb.title.basics.csv.gz
* imdb.name.basics.csv.gz
* imdb.title.principals.csv.gz
* bom.movie_gross.csv.gz

## Libraries used:

* import pandas as pd
* import seaborn as sns
* import matplotlib.pyplot as plt

## Working Files and Folders

* viz folder - contains all data vizualizations 
* zippedData - contains all data bases
* Module_1_Project.pdf - non-technical presentation of the results
* student.ipynb - main notebook file

## Jupiter Notebook file structure

#### Data cleaning, processing and preparing for vizualizations

* checking for missing values
* grouping using aggregate functions and setting up number of votes threshold
* joining databases
* chaning type of values
* creating new columns

#### Data vizualizations

* All Time Global Trends and Market Size

![Image 1](https://github.com/fipcio131/movie_analysis/blob/main/viz/global%20trends.png)

The motion movie industry showed a robust steady growth until the pandemic occurred. The uptrend should continue once all the industries begin to reopen .
In 2019 the mean gross profit was almost 30B dollars.

* Return of Investment and Gross Profit Trends

![Image 2](https://github.com/fipcio131/movie_analysis/blob/main/viz/STUDIOS%20AND%20MOVIES%20PROFITABILITY%202000%20-%202020.png)

For last 20 years the worldwide return of investment has been oscillating between 3 and 4 ratio while  domestic ROI has been close to 2. At the same time the movie industry has shown the a steady gross profit growth. 

* Major Studios Movies and Profit

![Image 3](https://github.com/fipcio131/movie_analysis/blob/main/viz/15%20MOST%20PROFITABLE%20STUDIOS%20AND%20MOVIES%201920%20-%202020.png)

The most successful and profitable turns out to be BV (Buena Vista Productions). Its movies reached gross profit of $17.5B for last 20 years.

* Genres Rating Analysis

![Image 4](https://github.com/fipcio131/movie_analysis/blob/main/viz/Genres.png)

The highest rated genre is documentary although the number of the documentary movies produced is one for the lowest among all genres. 


* BUDGET SIZE ANALYSIS

![Image 5](https://github.com/fipcio131/movie_analysis/blob/main/viz/Budget%20Analysis.png)

On the left we can see that in the most cases the higher production budget the higher gross income. However in terms of the ROI there is certain level of budget size that does not affect the ROI. Once the budget exceeds $100M the ROI always stays below 10 based on the available data.

## Key insights:

Industry Major Players - BV (Buena Vista Productions) The movie industry continues to grow steadily and provides higher profits and investment returns every year (except 2020) reaching $30b gross profit in 2019.

Mean worldwide return of investment has been oscillating between 3 and 4 ratio while  domestic ROI has been close to 2.
The most popular and highest rated genres are documentary, biography, history and war genres. However some supernatural movies show quite robust profits and return.

## Key recommendations:

In terms of the highest return of investment the best production budget size is up to $100M. Movies with higher budgets never exceed the ROI ratio of 10. The recommendation is to split funds into few smaller budget movies rather then one expensive. 

In terms of the genres the recommendation is to choose the highest rated genres in the following order: documentary, biography, history but also supernatural horrors

Even though the horror movie is the lowest rated genre, given a combination of a small production budget and good idea, this type can achieve significant ROIs.

For any potential cooperation with any production studios the best choice is BV. 

The best examples of the most profitable movies are: horrors like “Paranormal Activity” or “The Gallows” and documentary “Super Size Me”
