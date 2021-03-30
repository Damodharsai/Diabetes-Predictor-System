# Diabetes Predictor System

![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-blue.svg) ![Python 3.6](https://img.shields.io/badge/Python-3.6-brightgreen.svg) ![Scikit-Learn](https://img.shields.io/badge/Library-ScikitLearn-orange.svg)

This repository consists of files required for end to end implementation and deployment of Machine Learning Diabetes Predictor web application created with flask and deployed on the Heroku platform.

## Table of Contents
  * [App Link](#app-link)
  * [About the App](#about-the-app)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Technologies Used](#technologies-used)


## App Link
If you want to view the deployed model, click on the following link:<br />
[https://diabetespredictorsystemdsp.herokuapp.com/](https://diabetespredictorsystemdsp.herokuapp.com/)

A glimpse of the web app:

![image](https://user-images.githubusercontent.com/78199382/112999645-c0bd1c00-918c-11eb-96a5-a79110af7b08.png)

![image](https://user-images.githubusercontent.com/78199382/112999944-feba4000-918c-11eb-9d2b-a1dc8fece0a9.png)

![image](https://user-images.githubusercontent.com/78199382/113000461-7b4d1e80-918d-11eb-98fe-fef65c1f6b2b.png)


## About the App
The Diabetes Predictor is a flask web application which diagnostically predicts whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset like Pregnancies, Skin Thickness, BMI, Age, Glucose etc. The code is written in Python 3.6.10. Here, I have implemented various Classification techniques and since the dataset is fairly balanced in terms of 0 and 1 outcomes, the best accuracy which I could come up with was 77.604% using ensemble RANDOM FOREST classifier.

Note: In the dataset some independent variables(diagnostic measurement parameters) have '0' values like Insulin, Blood Pressure(which realistically can't be zero). So, I have tried to replace those '0' values by using imputer technique.

If you don't have Python installed, you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Deployement on Heroku
Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually to deploy this project.

[![](https://i.imgur.com/dKmlpqX.png)](https://heroku.com)

The next step would be to follow the instruction given in the [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 

