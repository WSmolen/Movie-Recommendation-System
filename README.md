# Movie-Recommendation-System

# Business Problem
Turner Classic Movies, launched in 1994, has been a mainstay for viewing classic films for almost 3 decades. TCM's estimated annual net revenue from cable fees is $200 Million with a budget of $20-40 Million. While still profitable the company has seen recent layoffs amidst of the merge of Warner Bros. and Discovery and the streaming landscape and viewers habits are rapidly changing. It's more important than ever to drive customer engagement with older films and in turn engagement with Turner Classic Movies. 

This recommendation system will allow anyone to rate any older films they have seen and be given high quality recommendations that the Network will be able to put on the platform and drive subscriptions and profit.
# Data Understanding
The Data is from MovieLens.org hosted at grouplens.org. It contains over 25 million reviews from 162,000 users on over 62,000 movies.
The Database was released December, 2019. Movie Title, year of release, each rating from individual users, genres and also user created tags are contained in the database.
# Data Analysis
The Data was filtered to movies up to the year 1969 as Turner Classic Movies focuses on classic films mostly from the 30s-60s. Most popular and highest rated movies were examined.
# Modeling
Multiple different machine learning algorithms were employed to make the most robust recommendation system. The surprise scikit python library was employed to make efficient recommendation models including K Nearest Neighbors, Negative Matrix Factorization and Singular Value Decomposition. Models performance was judged by Root Means Squared Error and Mean Absolute Error metrics.
# Appendix
https://ew.com/tv/tcm-insiders-detail-fight-to-protect-turner-classic-movies-network/
https://www.latimes.com/business/story/2023-06-29/how-profit-driven-turmoil-at-turner-classic-movies-placed-a-vast-cultural-heritage-at-risk
https://en.wikipedia.org/wiki/Turner_Classic_Movies
https://movielens.org/home
https://grouplens.org/datasets/movielens/
https://www.tcm.com/

# Repository Structure
├── Data                   # Zipped databases
├── .gitattributes         # Large File support
├── .gitignore             # ignored filetypes
├── Notebook.ipynb         # Data Exploration and Modeling
├── README.md              # Guide to this Repository

