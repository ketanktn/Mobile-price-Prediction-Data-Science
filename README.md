# Mobile-price-Prediction-Data-Science
Mobile Price Prediction in Data Science leverages machine learning to forecast smartphone prices by analyzing key features. This project covers data preprocessing, model selection, training, and evaluation, showcasing how predictive models can be applied to real-world pricing scenarios.

# The Problem
The data contains information regarding mobile phone features, specifications etc and their price range. The various features and information can be used to predict the price range of a mobile phone.

-Battery Power in mAh
-Has BlueTooth or not
-Microprocessor clock speed
-The phone has dual sim support or not
-Front Camera Megapixels
-Has 4G support or not
-Internal Memory in GigaBytes
-Mobile Depth in Cm
-Weight of Mobile Phone
-Number of cores in the processor
-Primary Camera Megapixels
-Pixel Resolution height
-Pixel resolution width
-RAM in MB
-Mobile screen height in cm
-Mobile screen width in cm
-Longest time after a single charge
-3g or not
-Has touch screen or not
-Has wifi or not


# About Data Set 
The columns available in the dataset are:

-Ratings: This field contains the various rating given by customers
-Ram: This field contain the Ram capacity of the phone in GB
-ROM: This is field contains the number of space available in the phone in GB
-Mobile_Size: This is the int size of the screen
-Primary_Cam: This is the number of pixels of the Back camera
-Selfi_Cam: The number of Pixels of the front camera
-Battery_Power: The battery power
-Price: The price of the mobile phone

# Methodology
We will proceed with reading the data, and then perform data analysis. The practice of examining data using analytical or statistical methods in order to identify meaningful information is known as data analysis. After data analysis, we will find out the data distribution and data types. We will train 4 classification algorithms to predict the output. We will also compare the outputs. Let us get started with the project implementation.

# What is a Machine Learning Model?
A machine learning model is a mathematical framework or algorithm designed to learn from data and make predictions or decisions based on that data. Instead of being explicitly programmed with specific instructions for every task, the model learns patterns and relationships from examples.

# How Does It Work?
-Data Collection:
  -The process begins with gathering relevant data. This data could be anything from images and text to numerical values and sensor readings.
  
-Data Preparation:
  -The collected data often requires cleaning and preprocessing. This step might include handling missing values, normalizing or scaling features, and encoding categorical variables.
  
-Choosing a Model:
  -There are various types of machine learning models, each suited to different types of tasks. Common types include:
    -Regression Models (predict numerical values, e.g., predicting house prices).
    -Classification Models (categorize data into classes, e.g., spam vs. non-spam emails).
    -Clustering Models (group similar data points, e.g., customer segmentation).
    -Recommendation Models (suggest items, e.g., movie recommendations).
    
-Training the Model:
  -During training, the model learns from the data by finding patterns and relationships. It uses algorithms to adjust its parameters in order to minimize errors in its predictions. This involves using a training dataset, which includes input features and known output labels.
  
-Evaluation:
  -After training, the model’s performance is evaluated using a separate dataset (validation or test set) that it hasn’t seen before. Metrics like accuracy, precision, recall, or mean squared error are used to assess how well the model performs.
  
-Hyperparameter Tuning:
  -Models often have hyperparameters (settings that control the training process) that need to be tuned to improve performance. This might involve techniques like grid search or random search.\
  
-Making Predictions:
  -Once the model is trained and evaluated, it can be used to make predictions on new, unseen data. For example, a trained image classification model can predict the category of new images.
  
-Deployment:
  -The final step is deploying the model into a production environment where it can interact with real-world data and provide value, such as making real-time recommendations or automating decisions.

# What is Linear Regression?
Linear regression predicts the relationship between two variables by assuming they have a straight-line connection. It finds the best line that minimizes the differences between predicted and actual values. Used in fields like economics and finance, it helps analyze and forecast data trends. Linear regression can also involve several variables (multiple linear regression) or be adapted for yes/no questions (logistic regression).

# What is Random forest?
Random forest, a popular machine learning algorithm developed by Leo Breiman and Adele Cutler, merges the outputs of numerous decision trees to produce a single outcome. Its popularity stems from its user-friendliness and versatility, making it suitable for both classification and regression tasks.

# Steps Involved in Random Forest Algorithm
-Step 1: In the Random forest model, a subset of data points and a subset of features is selected for constructing each decision tree. Simply put, n random records and m features are taken from the data set having k number of records.
-Step 2: Individual decision trees are constructed for each sample.
-Step 3: Each decision tree will generate an output.
-Step 4: Final output is considered based on Majority Voting or Averaging for Classification and regression, respectively.
