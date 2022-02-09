# Recommendations with IBM
## Installations:
1. Numpy
2. Matplotlib
3. Pandas
4. Seaborn
5. pickle

## Project Motivation:
The main motivation of this project is to analyze the interactions that users have with articles on the IBM Watson Studio platform,
and make recommendations to them about new articles you think they will like. In order to determine which articles to show to each user,
I have performed a study of the data available on the IBM Watson Studio platform. 
Three different types of recommendation systems were built:
- Rank Based Recommendations : find the most popular articles simply based on the most interactions and these are then the articles we might recommend to new users.
- User-User Based Collaborative Filtering: look at users that are similar in terms of the items a user has interacted with, and these items could then be recommended to the similar users.
-  Matrix Factorization: A machine learning approach to building recommendations -  Using the user-item interactions,a matrix decomposition is done. Using the decomposition,an idea of how well you can predict new articles an individual might interact with, is perceived.

## File Descriptions:
- Recommendations_with_IBM.ipynb : A jupyter notebook that contains the code for all the work I've done.
- articles_community.csv : contains 'aticle_id', 'email', 'title'
- user-item-interactions.csv : contains 'doc_body', 'doc_desc', 'doc_full_name', 'doc_status', 'article_id'

##  Licensing, Authors, Acknowledgements, etc:
I hereby acknowledge IBM and Udacity for giving me access to this dataset.

