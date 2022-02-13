# Portfolio
---
## Monitoring, Controlling and Cost reducing: Energy, Water and Gas consumption

### IoT Solution by LoRaWAN for [***McDonald’s restaurants***](https://www.mcdonalds.ro/restaurante)

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/arifulmrislam/McDonalds-Project)

<div style="text-align: justify">We have been working on a proof of concept since last year. We offered McDonald's to minimize their energy consumption. As well, their other consumption like water, gas and so on. We installed the LoRaWAN network in their one restaurant. Initially, we used five Eastron energy meters to collect different energy field consumption and observe the average consumption of twenty-four hours. We make a threshold that If the energy consumption is more than the set limit, It will create a notification and send it by mail. By getting this notification, customer will be informed about their unnecessary consumption. In this way, They can save their total energy cost at least 15% to 20%. We use the famous IoT platform Thingsboard and LoRaWAN based sensors.This year they approved our proof of concept, and We are working now with their other restaurants in Romania.</div>
<br>
<center><img src= "images/Restaurant Dashboard-5.png"/></center> <center><img src= "images/Restaurant Dashboard-6.png"/></center>
<br>

---
### Datalogging with ChirpStack, Node-RED, InfluxDB, Grafana using Docker Container

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/arifulmrislam/Datalogging-with-ChirpStack-Node-RED-InfluxDB-Grafana-with-Docker)

<div style="text-align: justify">I build a local solution for our customers without using cloud computing. First I installed ChirpStack network server, Node-RED, Influx DB & Grafana as Docker containers in the Dell server. I create a database in InfluxDB. Using this database, I connect Grafana web application which is the open-source analytics and monitoring solution for every database. I use a microtic gateway to forward all sensor values to the ChirpStack network server. ChirpStack allows Node-RED to collect the data from NS using a topic. After collecting those values I forward them to the InfluxDB database. Using those data I create a simple web dashboard in Grafana application to visualization the values in charts, graphs and alerts for notification of the critical situation.</div>
<br>
<center><img src="images/Node-Red, Grafana, Docker and Telegraf with Influxdb.png"/></center>
<br>

---
### Advantech LoRaWAN WISE-6610 gateway and WISE-2410 wireless condition monitoring sensor solution

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/arifulmrislam/Advantech-LoRaWAN-WISE-6610-gateway-and-WISE-2410-wireless-condition-monitoring-sensor-solution)

<div style="text-align: justify">For predictive maintenance, I used WISE-2410 transmits sensor data to WISE-6610 (via LoRaWAN) or 3rd party LoRaWAN gateway (via LoRaWAN). WISE-6610 provides Ethernet connectivity and supports Modbus TCP, RESTful Web API for integration. The WISE-6610 allows for VPN tunnel creation with various protocols that ensure safe communication. It also provides a network server that can encrypt and convert LoRaWAN data in the device, and its redundancy-enhanced functions are specifically designed to prevent connection loss. It has an inbuilt application server. Using this application server, I build a dashboard in node-red to visualization the WISE-2410 values.  </div>
<br>
<center><img src="images/System Architecture.png"></center>

<center><img src="images/Dashboard.png"></center>
<br>

---
### Detect Spam Messages: TF-IDF and Naive Bayes Classifier

[![Open Notebook](https://img.shields.io/badge/Jupyter-Open_Notebook-blue?logo=Jupyter)](projects/detect-spam-nlp.html)
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/chriskhanhtran/detect-spam-messages-nlp/blob/master/detect-spam-nlp.ipynb)

<div style="text-align: justify">In order to predict whether a message is spam, first I vectorized text messages into a format that machine learning algorithms can understand using Bag-of-Word and TF-IDF. Then I trained a machine learning model to learn to discriminate between normal and spam messages. Finally, with the trained model, I classified unlabel messages into normal or spam.</div>
<br>
<center><img src="images/detect-spam-nlp.png"/></center>
<br>

---
## Data Science

### Credit Risk Prediction Web App

[![Open Web App](https://img.shields.io/badge/Heroku-Open_Web_App-blue?logo=Heroku)](http://credit-risk.herokuapp.com/)
[![Open Notebook](https://img.shields.io/badge/Jupyter-Open_Notebook-blue?logo=Jupyter)](https://github.com/chriskhanhtran/credit-risk-prediction/blob/master/documents/Notebook.ipynb)
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/chriskhanhtran/credit-risk-prediction)

<div style="text-align: justify">After my team preprocessed a dataset of 10K credit applications and built machine learning models to predict credit default risk, I built an interactive user interface with Streamlit and hosted the web app on Heroku server.</div>
<br>
<center><img src="images/credit-risk-webapp.png"/></center>
<br>

---
### Kaggle Competition: Predict Ames House Price using Lasso, Ridge, XGBoost and LightGBM

[![Open Notebook](https://img.shields.io/badge/Jupyter-Open_Notebook-blue?logo=Jupyter)](projects/ames-house-price.html)
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/chriskhanhtran/kaggle-house-price/blob/master/ames-house-price.ipynb)

<div style="text-align: justify">I performed comprehensive EDA to understand important variables, handled missing values, outliers, performed feature engineering, and ensembled machine learning models to predict house prices. My best model had Mean Absolute Error (MAE) of 12293.919, ranking <b>95/15502</b>, approximately <b>top 0.6%</b> in the Kaggle leaderboard.</div>
<br>
<center><img src="images/ames-house-price.jpg"/></center>
<br>

---
### Predict Breast Cancer with RF, PCA and SVM using Python

[![Open Notebook](https://img.shields.io/badge/Jupyter-Open_Notebook-blue?logo=Jupyter)](projects/breast-cancer.html)
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/chriskhanhtran/predict-breast-cancer-with-rf-pca-svm/blob/master/breast-cancer.ipynb)

<div style="text-align: justify">In this project I am going to perform comprehensive EDA on the breast cancer dataset, then transform the data using Principal Components Analysis (PCA) and use Support Vector Machine (SVM) model to predict whether a patient has breast cancer.</div>
<br>
<center><img src="images/breast-cancer.png"/></center>
<br>

---
### Business Analytics Conference 2018: How is NYC's Government Using Money?

[![Open Research Poster](https://img.shields.io/badge/PDF-Open_Research_Poster-blue?logo=adobe-acrobat-reader&logoColor=white)](pdf/bac2018.pdf)

<div style="text-align: justify">In three-month research and a two-day hackathon, I led a team of four students to discover insights from 6 million records of NYC and Boston government spending data sets and won runner-up prize for the best research poster out of 18 participating colleges.</div>
<br>
<center><img src="images/bac2018.JPG"/></center>
<br>

---
## Filmed by me

[![View My Films](https://img.shields.io/badge/YouTube-View_My_Films-grey?logo=youtube&labelColor=FF0000)](https://www.youtube.com/watch?v=vfZwdEWgUPE)

<div style="text-align: justify">Besides Data Science, I also have a great passion for photography and videography. Below is a list of films I documented to retain beautiful memories of places I traveled to and amazing people I met on the way.</div>
<br>

- [Ada Von Weiss - You Regret (Winter at Niagara)](https://www.youtube.com/watch?v=-5esqvmPnHI)
- [The Weight We Carry is Love - TORONTO](https://www.youtube.com/watch?v=vfZwdEWgUPE)
- [In America - Boston 2017](https://www.youtube.com/watch?v=YdXufiebgyc)
- [In America - We Call This Place Our Home (Massachusetts)](https://www.youtube.com/watch?v=jzfcM_iO0FU)

---
<center>© 2021 Ariful Islam Arif. Powered by Jekyll and the Minimal Theme.</center>
