# DATA SCIENCE PORTFOLIO
This repository contains my Data Science projects. All projects was created using iPython format.

## Table of Contents
1. [Machine Learning](#machine-learning)
   - Hardcorals and Softcorals Recognition using YOLOv4 Custom Detector
   - Public Sentiment Analysis using Naive Bayes
   - Underdeveloped Country Clustering using K Means
2. [Data Exploration](#data-exploration)
   - IMBD Movie Simple Data Exploration using SQL Query

### Machine Learning
- [Hard and Soft Corals Recognition using YOLOv4 Custom Detector](https://github.com/rainaldyd/Portfolio/blob/main/Machine%20Learning/Hardcorals%20and%20Softcorals%20Recognition%20using%20YOLOv4%20Custom%20Detector.ipynb): YOLOv4 method is used to recognize hard and soft corals genus or species. In this project, I build YOLOv4 custom detector model based on [theAIGuys](https://github.com/theAIGuysCode/YOLOv4-Cloud-Tutorial) YOLOv4 model. The workflow of this project is (1) clone YOLOv4 repository, (2) manually label images using annotation tools, (3) configure files for training, (4) train the model, and (5) model quality check based on Mean Average Precision (mAP) value. This project is run on Google Collab and still unfinished (stuck at training custom model, GPU problem).
- [Public Sentiment Analysis using Naive Bayes](https://github.com/rainaldyd/Portfolio/blob/main/Machine%20Learning/Public%20Sentiment%20Analysis%20using%20Naive%20Bayes.ipynb): Gaussian Naive Bayes method is used to classify DKI Jakarta resident sentiment of Indonesia capital city transfer to Penajam Paser Utara, East Kalimantan. The analysis result answered 2 questions: (1) Do they agree or disagree to transfer the capital city to East Kalimantan? and (2) What is the reason or cause of their agreement/disagreement? This project includes Data collection using twitter API, Text data wrangling, Text analysis, and Topic analysis with Hyperparameter tuning.
- [Underdeveloped Country Clustering using K Means](https://github.com/rainaldyd/Portfolio/blob/main/Machine%20Learning/Underdeveloped%20Country%20Clustering%20using%20K%20Means.ipynb): K-Means Clustering method is used to cluster which underdeveloped countries are the most urgent and the most need to be helped by NGO. This project include Exploratory analysis (EDA), Data wrangling, dan 3D Data visualization.

### Data Exploration
- [IMBD Movie Simple Data Exploration using SQL Query](https://github.com/rainaldyd/Portfolio/blob/main/Data%20Exploration/IMBD%20Movie%20Simple%20Data%20Exploration.ipynb): Import dataset from IMDB Movies database using SQL query requested using Python and then do analysis, such as directors with the most movies, highest earning movie directors, most profitable movies, and visualizing the movie budget distribution of a particular year.
