# Wayne_Portfolio
Welcome to my portfolio<br>
These projects are my previous works and exercises. I will continue to add more projects to enhence my capabilities in data science and machine learning.<br>
Thanks for reading!<br>

---

# [Project 1: Data Visualization - Netflix](https://github.com/huihuang751/Data-Visualization-Project_Netflix)
The purpose of this project is to practice data visualization and exploratory data analysis.
The dataset contains 8000 Netflix movies and TV Shows data from [kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows).<br>

## Part1: Data cleaning
Basic look of dataset, data cleaning, correct data type.

## Part2: Visualization

![](/images/part1.png)<br>
We can observe that movies and TV shows dramatically increase in the past decade. However, it slowed down since 2019.<br>
It should be influenced by COVIN-19 in 2019.<br><br>
In top 10 countries, USA and UK are not surprisingly in top 1 and top 3, but India is top 2.<br>

---
![](/images/movies%20and%20tv%20shows%20difference.png)<br>
In top 10 countries, there are huge different preference on Movies and TV Shows. Movies are more likely released in India, and TV shows are more popular in S. Korea. <br>
Maybe Indians are interested in Bollywood, so Netflix offers more movies. On the other hands, S. Korea is well-known with their TV shows, such as squid game, thus it is in expectation that S. Korea has more TV shows on Netflix.<br/>

---
![](/images/Offset.png)<br>
It is clearly that movies and TV shows reduced after 2019. Now, we found that TV shows still have slightly increase while movies have significantly decreased. Maybe it is because COVID-19 caused film industry stop filming temporarily.<br>

---
![](/images/Content%20released%20by%20countries.png)<br>
Here we check movies and TV shows trend in each top 10 countries and find that TV shows actually increased in USA after 2019.<br>
It is possible that most americans need to stay at home and they are more likely to watch TV shows, so Netflix releases more TV shows to meet their preferences.

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
