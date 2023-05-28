## Movie Industry Analysis
### Author: Paul Mbuitu Muriithi

### Overview
I have been tasked with assisting Microsoft in their venture into the movie industry. My goal was to explore what type of films are currently doing the best at the box office and to provide these findings to Microsoft's new movie studio executives. My analysis of the movie industry, achieved by garnering data and utilizing descriptive statistics and visualizations. By allocating 22 million to 24 million dollars to produce a movie released in July, January, August or November, the data shows that a movie studio will be extremely likely to succeed. I have also given recommendations as to which directors should be hired for a **Drama, Comedy, or Thriller** movie. Microsoft can use this report to target their production budget, genre, release-time, and crew members of their upcoming movie endeavors to generate the highest amount of revenue possible.

### Business Problem
Microsoft wants a piece of the multi-billion dollar movie-making industry, but they are unsure of where to begin. The challenge is that they lack the knowledge to move forward for their new movie studio. To assist them with this goal, I'll analyze the movies that have been most successful recently, I will make recommendations about attributes that Microsoft's movies should have in order to achieve the highest revenue. 

### Main Objective
To explore the types of films that have been performing exceptionally well at the box office and extract actionable insights that can guide the decision-making process for Microsoft's new movie studio.

### Specific Objectives
* To find out what movie type Genres are currently most successful.
* To find out what budget amount tends to achieve the highest box office gross.
* To find out when is the most lucrative time of year to release a movie.

### Notebook Structure
* Reading the Data
* Data Wrangling
* Exploratory Data Analysis
* Conclusions
* Recommendations

### Data Understanding
The data was collected from various locations, the different files have different formats. Some are CSV or TSV files that can be opened using spreadsheet software or pd.read_csv, while the data from IMDB is located in a SQLite database. 

The data includes different information concerning the movies ranging from the title, genres, average-rating, e.t.c

Analyzing dataset will determine what contributes to the success of a movie. In this analysis, I will define analysis in financial terms basing the success of a movie on the amount of money it earns in comparison to the budget.

### Data Wrangling
Out of the several datasets that were collected, only some features and rows are relevant to the process. Therefore, in this step, the features that are not required from each dataset were dropped. The remaining datasets were then joined.

### Exploratory Data Analysis
Income ratio(worldwide_gross/production_budget) for each movie was found.
A successful movie was determined on condition that its worldwide gross is at least double its production budget.
<img src = 'images\output1.png' />
A correlation between production budget and the income ratio was found.
<img src = 'images\output2.png' />
The most lucrative time of year to release a movie was also determined.
<img src = 'images\output3.png' />
Crew members(directors) with a history of proven successful movies was found.
<img src = 'images\output5.png' />

### Conclusion
* The combination of Action, Drama and Romance genres had the highest average income ratio.
* Drama movies are the most common genres in successful movies.
* Production budget for a movie can be around $22,000,000.
* Movie release months were fairly distributed throught the year and the best three months to releae a moving considering the income ratio is on July, January and August.

### Recommendations
* I would recommend that Microsoft release movies with three genres which include **Drama, Comedy and Thriller**
* Overall, the genre combination: **(Action, Drama, Romance)** topped with being the highest in terms of income ratio and it's worth taking note of.
* Production budget should be 22 to 24 million dollars.
* Release month should be July, January, or August and directed by a top-grossing director with a history of proven successful **Drama, Comedy, or Thriller** movies.