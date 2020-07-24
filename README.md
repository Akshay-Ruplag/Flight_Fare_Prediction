# Flight Fare Prediction: 

## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Installation](#installation)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Directory Tree](#directory-tree)
  * [Bug / Feature Request](#bug---feature-request)
  * [Future scope of project](#future-scope)


## Demo
Link: [https://flight-fare-predictor-app.herokuapp.com/](https://flight-fare-predictor-app.herokuapp.com/)

[![](https://i.imgur.com/R1g2wvC.png)](https://flight-fare-predictor-app.herokuapp.com/)


## Overview
This is a Flask web app which predicts fare of Flight. The data used for this model is obtained from Kaggle.com. I made a use of GadientBoosting algorithm for ML Model, flask framework for API creation and HTML for front end.  

## Motivation
You actually don't get a feel of a Machine Learning model untill you deploy it and make it available to the rest of the world to use and get benefits out of it. An attractive GUI would be a cheery on the top. I always wanted to make an end to end machine learning project and not just a model building or data analysis. This drives me towards the achieving an end product which you can see and use.

## Installation
The Code is written in Python 3.7.3. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Deployement on Heroku
I made use of Heroku for deplying my ML model. Heruko is Free cloud platform for deployment for single user and max limit for app deployment is 5. 
Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually deploy this project. I connected my GitHub account for the deployment. 

[![](https://i.imgur.com/dKmlpqX.png)](https://heroku.com)

Our next step would be to follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

## Directory Tree 
```
├── static 
│   ├── css
├── template
│   ├── home.html
├── Procfile
├── README.md
├── app.py
├── flight_fare_prediction.ipynb
├── flightFare_GB.pkl
├── requirements.txt
```

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 

I made use of Jyputer Notebook to write a code for Exploratory data Analysis,feature Engineering, Feature Selection and ML model building. Then I made use of Spyder IDE for writing FLask and HTML code. 


## Bug / Feature Request

If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an [issue](https://github.com/Akshay-Ruplag/Flight_Fare_Prediction/issues) here by including your search query and the expected result.

## Future Scope

* Optimize Flask app.py
* Front-End 
