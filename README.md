# ds4ph_finalproject
Biomedical Data Science Final Project

- Link to the app: https://sandyshi.shinyapps.io/flexdash_finalproject/

- **Introduction:** Welcome to the diabetes prediction app! This app aims to provide predictions on the chance a user will develop diabetes which hopefully can remind users to be aware of the importance of having healthier diets and living habits to reduce the chance of developing diabetes. The data set is retrieved from Kaggle and the data is about the different factors that are associated with the development of diabetes. It has 9 variables (8 factors & 1 outcome) and 2000 observations. It was used to train and test the SVM and RF models and provide predictions on the chance of developing diabetes based on BMI, age, glucose level, blood pressure, and 4 other factors.  


- **User guide:** There are a total of 4 panels in this app. The overview panel provides some basic statistics about the prevalence of diabetes in the United States in the past few years. The “model evaluation on 2000 patient data” panel gives the evaluations of the two models we built using the diabetes data set. The “test your chance of having diabetes” panel allows users to test their chance to develop diabetes based on the information they provide. The two prediction models used in this app are support-vector machine (SVM) and random forest (RF). After users inputting all the required information, both models will give predictions on the chance of developing diabetes. Last, this “about the app” panel provides introduction and user guide of this app to the users.


- **About the prediction model:** our first model was built using support-vector machine (SVM), and the second model was built using random forest (RF). Both models were built using the first data set and have accuracy above 80%. To run this app locally, download the data and model files from the Github project submission repository to your local directory



- **Creators:** Shunyao Lei, Junyuan(Sandy) Shi, & Zihui Ou

- **Last updated:** 05/18/2021

- **References:** 
  + https://www.kaggle.com/vikasukani/diabetes-data-set
  + https://www.cdc.gov/diabetes/pdfs/data/statistics/national-diabetes-statistics-report.pdf
