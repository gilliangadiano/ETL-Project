# Bad Words the SQL (ETL-Project)
The purpose of this project is to determine if there is a correlation between the frequency(count) of bad words and the rating of the movie. 
We're asking: "Do people like movies that have a s---ton of f----ng bad words?"   =)
 
We analyzed all the available scripts from the IMSDB website and focused on counting the frequency of 11 of the most common 'bad words' appearing in each movie script. 
We also pulled additional data from OMDBApi.com prior to graphing the data with MatPlotLib 

# This repo contains the collaborative work for Team 2. 
# You will find the following:
### Resources Folder
Contains each team member's Jupyter Notebook that contains code used for later parts of the project
   * `gillian_notebook.ipynb` - web scraping code to pull movie titles and URLs from IMSDB website and convert to DataFrame
   * `sarah_notebook.ipynb` - code to pull the word count of each 11 bad words and add data to DataFrame
   * `safwan_new.ipynb` - code to pull genre, release date, run time, MPAA rating, and IMDB review score from OMDBApi website 
   * `zach_notebook.ipynb` - code that pushes data into MySQL database 
   * `droppingNullRows.sql` - SQL code that cleans up Null values from database. 

### Output Folder
Contains output CSV files from Jupyter notebooks
   * `movie_list.csv` - raw data scraped from IMSBD
   * `clean_movie_list.csv` - cleaned up data that contains the movies that were used in the analysis 
   * `movie_counts.csv` - contains the count of each of the 11 bad words found in each of the movie scripts. 
   * `result.csv` - added genre, release date, run time, MPAA rating, and IMDB review score 

#### PowerPoint presentation 
Summarizes the project: contains problems statment, challenges/limitations, graphs, and ways to improve the analysis. This includes speaker notes to elaborate on each slide.
 
#### Project Statement.docx 
 * Word document submitted prior to starting project - containing initial project statement, goals, data sources 

