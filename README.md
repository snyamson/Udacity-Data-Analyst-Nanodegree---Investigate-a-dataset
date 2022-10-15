# Project Overview
In this project, I will analyze a dataset and then communicate my findings about it. I will use the Python libraries NumPy, Pandas, and Matplotlib to make my analysis easier

# What do you need to run this project?
You need an installation of Python, plus the following libraries:
- Pandas
- NumPy
- Matplotlib
> I recommend installing Anaconda, which comes with all of the necessary packages, as well as IPython notebook.

# Motivation
In this project, I will go through the data analysis process and see how everything fits together.
I'll use the Python libraries NumPy, pandas, and Matplotlib, which make writing data analysis code in Python a lot easier! Not only that, these are sought-after skills by employers!

# What did I learn?
- I know all the steps involved in a typical data analysis process
- I am comfortable posing questions that can be answered with a given dataset and then answering those questions
- I know how to investigate problems in a dataset and wrangle the data into a format I can use
- I now have experience communicating the results of my analysis
- I'am able to use vectorized operations in NumPy and pandas to speed up my data analysis code
- I'am familiar with pandas' Series and DataFrame objects, which let me access my data more conveniently
- I know how to use Matplotlib to produce plots showing my findings

# Project Details: Introduction & Dataset Description
The Movie Database is an online crowdsourced database for move and television information. The metadata on movies and TV shows is contributed by the 1.1 million-strong community.The dataset contains information about 10,000 movies from the Movie Database (TMDb) with released year from 1966 to 2015, including user ratings and revenue.
The dataset is in a comma-seperated-values (.csv) format. The dataset contains 21 colums and 10866 rows.
- Certain columns, like ‘cast’ and ‘genres’, contain multiple values separated by pipe (|) characters.
- There are some odd characters in the ‘cast’ column. Don’t worry about cleaning them. You can leave them as is.
- The final two columns ending with “adj” show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time.

# Project Details: Questions Investigated
- What are the top 20 actors with the highest profits?
- What are the top 20 actors with the the most appearances in movies?
- How many movies based on their genres were produced?
- What genre of movies have higher popularity?
- What are the top movies based on revenue, budget, popularity and average votes?
- Does movie runtime affect it adjusted revenue and budget?

# Project Details: Conclusion
After Investigating the Dataset, the following conclusions can be drawn:

- The Top 3 actors with higher profits are Robert MacNaughton, Daisy Ridley and Betty Lou Gerson.
- Robert De Niro is the actor with the most appearances in the movies, closely followed by Samuel L. Jackson and Bruce Willis, while Willem Dafoe became the last actor.
- When compared to other genres, drama films are the most common. Drama, Comedy, and Thriller are the top 3 most popular movie genres overall and according to this dataset for the years 1960 – 2015.
- According to the popularity index, the most popular movie genres are Adventure, followed by Science Fiction, Fantasy and Action while least popular genre is Mystery.
- Based on the analysis, the movie Avatar is ranked first in terms of revenue, The Worrior's Way is the movie with the highest budget, the Jurassic World is the most popular movie and The Story of Film: An Odyssey is the movie with the highest average votes.
- It can be seen from the scatter plots of the association between movie runtime, adjusted revenue, and budget that the majority of movies have runtimes between 100 and 200 minutes, which is also the range for both adjusted revenue and adjusted budget. This implies that films with shorter runstimes are more likely to earn more money and have a larger budget.
