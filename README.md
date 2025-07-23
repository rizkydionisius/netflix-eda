# Netflix Titles EDA

Exploratory Data Analysis (EDA) on Netflix Movies & TV Shows dataset to find insights about the content available on the platform.

## Dataset
Source: sample dataset of 200 Netflix titles.  
Columns: type, director, cast, country, date_added, release_year, rating, duration, listed_in, description.

## Objectives
- What is the proportion of Movies vs TV Shows?
- How many titles are added each year?
- Which countries produce the most content?
- What are the most common genres?
- What are the most frequent themes in descriptions?

## Tools & Libraries
- Python
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- wordcloud

## Key Insights
- About 63.5% of titles are Movies, and 36.5% are TV Shows.
- Most titles in this sample were added in 2021.
- Many titles have unknown country info, but United States dominates among known entries.
- The most common genre is Dramas.
- Common themes in descriptions include family, love, friendship, and life challenges.

## How to Run
1. Clone this repository:  
   `git clone https://github.com/rizkydionisius/netflix-eda.git`

2. Install dependencies:  
   `pip install pandas numpy matplotlib seaborn wordcloud jupyter`

3. Launch Jupyter Notebook:  
   `jupyter notebook`

4. Open and run `netflix_analysis.ipynb`.

## Author
Made by Rizky Dionisius  
GitHub: [rizkydionisius](https://github.com/rizkydionisius)
