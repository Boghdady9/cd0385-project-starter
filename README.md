Bike Sharing Demand Prediction using AutoGluon Framework
This project aims to predict bike-sharing demand using the AutoGluon framework and perform feature engineering on the provided dataset. The dataset used in this project was provided by Hadi Fanaee Tork on the Kaggle platform.

About Bike Sharing Systems
Bike-sharing systems are automated networks of rental bicycles that allow users to rent bikes from one location and return them to another location as per their convenience. These systems are widely used in cities worldwide, offering a flexible and environmentally friendly mode of transportation.

Dataset Description
The dataset contains information collected from bike sharing systems, including the duration of travel, departure location, arrival location, and time elapsed. This data has been made available for research purposes and provides a valuable resource for developing predictive models.

Project Objective
The main objective of this project is to predict the demand for bike sharing based on various factors such as time of day, weather conditions, and other relevant features. The AutoGluon framework will be utilized to automate the machine learning pipeline, including feature selection, model training, and hyperparameter optimization.

AutoGluon Framework
AutoGluon is an open-source framework developed by AWS that automates the process of building and deploying machine learning models. It provides a high-level API that simplifies the task of training and evaluating models, making it suitable for both beginners and experienced machine learning practitioners.

Project Workflow
Data Preparation: The dataset will be preprocessed and cleaned to handle missing values, outliers, and other data quality issues. Feature engineering techniques will be applied to derive additional meaningful features from the existing ones.

Feature Selection: Automatic feature selection methods provided by AutoGluon will be employed to identify the most relevant features for the prediction task.

Model Training: AutoGluon will be used to train multiple machine-learning models on the dataset. The framework will automatically select and tune the best models based on the provided evaluation metric.

Model Evaluation: The trained models will be evaluated using appropriate evaluation metrics such as mean squared error (MSE) or root mean squared error (RMSE). The performance of the models will be compared to identify the best-performing one.

Requirements
To run this project, ensure that the following libraries are installed:

Copy
$ pip install autogluon
$ pip install "mxnet<2.0.0"
$ pip install matplotlib
$ pip install pandas

Project Status
The project has been successfully implemented and completed.
