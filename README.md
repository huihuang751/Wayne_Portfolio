# Wayne_Portfolio
Welcome to my portfolio<br>
These projects are my previous works and exercises. I will continue to add more projects to enhence my capabilities in data science and machine learning.<br>
Thanks for reading!<br>

---

# [Project 1: Data Visualization - Netflix](https://github.com/huihuang751/Data-Visualization-Project_Netflix)
The purpose of this project is to practice data visualization and exploratory data analysis.
The dataset contains 8000 Netflix movies and TV Shows data from [kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows).<br>

In this project, I focus on data cleaning, exploratory data analysis, and finding special insigts.

![](/images/part1.png)<br>

![](/images/movies%20and%20tv%20shows%20difference.png)<br>

---

# [Project 2: IMDB sentiment prediction](https://github.com/huihuang751/NLP_project-IMDB_Sentiment_Prediction)
In this exercise, several classifier models, such as SVM, decision tree, and logistic regression, are applied to predict sentiment of reviews.
IMDB dataset having 50K movie reviews for natural language processing or Text analytics. We use a set of 25,000 highly polar movie reviews for training and 25,000 for testing.

## Result

![](/images/Score.png)

## Conclusion
* Logistic Regression successfully achieve 82% F1 score. 
* Adjusting models' paramters by GridSearchCV, F1 score does not have significant improvement (opt).
* Further clean text by using stop word method keeps F1 score (Cln).
* We suspect it is resulted from bag-of-words method (One-hot encoding).
* One-hot encoding would cause curse of dimensionality and sparse vectors.
