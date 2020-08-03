# DELL-Forecast-Accuracy
This is a supply chain project focused on Analyzing the prediction accuracy of Dell's hardware products demand

*Note: This is a brief description of my Capstone project with Dell, hence data used will not be available for public view

![image](https://user-images.githubusercontent.com/47016027/89138187-c3d21080-d508-11ea-9abf-2b7a8095e8bd.png)

# Project Objectives 
Dell’s Global Operation Storage and Services Supply Chain Data & Analytics is interested in an Analytical model to establish stock-outs risks for purchased parts required to fill customer demand over a rolling 8-week window. The ability to predict a stock-out benefits Dell’s customers by allowing supply chain to mitigate or balance expedite expenses vs increasing the lead time of products at the time of customer quote or order. 
Both descriptive analytics and prescriptive analytics were used to solve the following objectives laid out by Dell;

1.	Identify gaps/ variability in the predicted quantity of materials demanded (MRP demand) vs actual quantity of materials demanded(quantity booked). 
2.	Analyze various factors affecting these variability.
3.  Prescribe solutions to fix these variability.
# Exploratory Analysis
![image](https://user-images.githubusercontent.com/47016027/89138733-7eaede00-d50a-11ea-95bf-47ad1f567735.png)
![image](https://user-images.githubusercontent.com/47016027/89138763-95edcb80-d50a-11ea-9dac-73210f8a1c56.png)

# Methodology
The machine learning technique employed in this model building process is Decision Tree. This technique is used to model the relationship between two or more independent variables and a dependent variable

![image](https://user-images.githubusercontent.com/47016027/89138823-d4838600-d50a-11ea-9e81-2c35ee0aac1b.png)
# Evaluation
The validation technique used for this model is 10-fold cross validation. Cross-validation is a statistical method used to estimate the skill of machine learning models on unseen data. This means using a limited sample in order to estimate how the model is expected to perform in general when used to make predictions on data not used during the training of the model
# Confusion matrix
![image](https://user-images.githubusercontent.com/47016027/89138927-304e0f00-d50b-11ea-993b-5c225b0d24c6.png)
