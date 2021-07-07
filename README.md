<p align="center">
  <h3 align="center">Rain Prediction</h3>

  <p align="center">
    This project involves exploratory data analysis, data pre-processing, training multiple baseline machine learning models, hyperparameter tuning and building ensemble models to predict next-day rain in Australia.
  </p>
</p>

<h3 id="about-the-project">About The Project</h3>

<b>Data source:</b>
<br>
https://www.kaggle.com/jsphyg/weather-dataset-rattle-package

<b>This project was built with:</b>
<br>
* [Scikit-learn](https://scikit-learn.org/)
* [Matplotlib](https://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/)
* [Pickle](https://docs.python.org/3/library/pickle.html)

<h3 id="summary">Project Summary</h3>

<div align="left">
  <ol>
    <li>
      <b>Data Understanding</b>  
      - Descriptions of variables
    </li>
    <li>
      <b>Exploratory Data Analysis</b> 
      - Exploring the categorical and numerial variables
      - Feature engineering of Date variable
      - Outlier detection using boxplots
      - Checking the distribution of numerical variables using histograms
      - Checking the distribution of target variable (class distribution)
      - Correlation analysis
      - Checking for duplicates
    </li>
    <li>
      <b>Data Pre-processing</b> 
      - Handling missing values
      - Removing outliers
      - Categorical data encoding
      - Feature scaling
    </li>
    <li>
      <b>Training Baseline Models</b> 
      - Created a function to evaluate performance of multiple models using multiple metrics through Cross Validation
      <img src="model_performance.PNG" alt="performance evaluation">
    </li>
    <li>
      <b>Feature Selection</b> 
      - Principal Component Analysis (PCA)
    </li>
    <li>
      <b>Shortlisting the Best Models</b> 
      - Selected 3 best models
    </li>
    <li>
      <b>Hyperparameter Tuning</b> 
      - Determined the best parameters of the models using Randomized Search Cross Validation
    </li>
    <li>
      <b>Building Ensemble Models</b> 
      - Built 3 ensemble models using Stacking Classifier
    </li>
    <li>
      <b>Model Evaluation</b> 
      - Evaluated the performance of the 3 inital shortlisted models and the 3 ensemble models
      - Plotted learning curves to compare the performance of the models on training and testing data
      - Determined the best model
    </li>
  </ol>
</div>

