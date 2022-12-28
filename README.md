# BangaluruHomePrediction

![](BHP_website.png)

This data science project is "real estate price prediction website". 

**Bangalore Home Prices Data Set used**
https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data


We build a model using sklearn and linear regression using banglore home prices dataset from kaggle.com. <br>
Second step would be to write a python flask server that uses the saved model to serve http requests. <br>
Third component is the website built in html, css and javascript that allows user to enter home square ft area, bedrooms etc and it will call python flask server to retrieve the predicted price. During model building we did data loading and cleaning, outlier detection and removal, feature engineering, dimensionality reduction, gridsearchcv for hyperparameter tunning, k fold cross validation.


**Technology and tools used**
1. Python
2. Numpy and Pandas for data cleaning
3. Matplotlib for data visualization
4. Sklearn for model building
5. Jupyter notebook, visual studio code and pycharm as IDE
6. Python flask for http server
7. HTML/CSS/Javascript for UI
