# House Price Prediction

Thousands of houses are sold every day. There are some questions every buyer asks himself like: What is the actual price that this house deserves? Am I paying a fair price? In this paper, a machine learning model is proposed to predict a house price based on data related to the house (its size, the year it was built in, etc.). In this project, Python programming language with a number of Python packages will be used. In this project I have attempted to predict the price of a house. I hope I achieve this by the end of this project. 

## Details of the project:

### Data Description:

![image](https://user-images.githubusercontent.com/68365712/197681328-b10be27a-ac7e-4945-ae78-430b9e033265.png)

### Data Information:

![image](https://user-images.githubusercontent.com/68365712/197681432-79c20754-97bc-461b-b1d5-0cde8d98a02b.png)

### Dataset Description:

![image](https://user-images.githubusercontent.com/68365712/197681490-2251707b-ec10-4691-a822-b9fe76744f9a.png)

### EDA
This has been done and can be viewed in the report.pdf which I have already shared in this repository.

### Correlation plot

![image](https://user-images.githubusercontent.com/68365712/197681676-f34325af-0b48-428a-a528-0d3590e82d4b.png)


### Metrics for each model

![image](https://user-images.githubusercontent.com/68365712/197681815-42f700e5-c1c7-456c-80e3-1f75425b35fd.png)
![image](https://user-images.githubusercontent.com/68365712/197681837-181573a5-7f49-4e2c-bee8-702e9c786c6e.png)
![image](https://user-images.githubusercontent.com/68365712/197681854-e0130a5c-6479-4e82-9bda-b05de0eb45d5.png)

### Graphical visualization of the model I chose

![image](https://user-images.githubusercontent.com/68365712/197682214-14696901-047b-4d0a-bd29-7ae8df47724f.png)


### Conclusion
We first understood the data, cleaned the data, processed the data which was helpful in understanding the data as well as predict. Then we saw all the possible plots in the exploratory data analysis. For modelling we compared two models, Linear Regression and Ridge. We calculated the R squared error, Mean square error, Mean absolute error and the Mean absolute percentage error with help of the train data and compared with both the models. So we can see that the metrics of normalized Ridge model is lesser compared to that of Linear Regression model. After that I tried XGB Regressor from XGBoost. Since the gradient boosting regressor had more accuracy, we chose that. 
Even if the model is accurate, sometimes the model with lower accuracy rate can outperform the model with higher accuracy.
