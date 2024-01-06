# Info

I along with my partner Steven Alvarado ([GitHub](https://github.com/Steven-Alvarado)) created two algorithms to identify the temperature changes from around the world and to see the effects it had to the land and ocean. The recorded global temperature dataset we used came from UC Berkley. The data in both algorithms are represented quarterly, meaning we use the temperatures of each season for the regression models; 1st quarter -> March | 2nd quarter -> June | 3rd quarter -> September | 4th quarter -> December. The recorded data starts back in 1850 and stops at 2015. The regression models are explained below.

## Simple Linear Regression

For the simple linear regression model the data is processed by using the dates, Land_Average_Temperature, and Land_And_Ocean_Average_Temperature columns only. We disregarded the use of the uncertainty and max/min temperature columns due to it not giving any relevant information for the model and would provide us incorrect results. From their I made four X values and eight Y values which represent the 4 quarters of each season (the extra 4 Y values represents the Land and Ocean Average temperatures); X representing time and Y representing temperatures. The dataset is split into the training and Test set and the linear regression model is set up on the training set. I print out the predicted test set results for the Land Average Temperatures and the Land_And_Ocean_Average temperatures. The predicted data is used in our scatter plot to provide information on the temperature changes. In both the Land as well as Land_And_Ocean average temperatures showed rising temperature increases proving that climate change is real and is affecting the entire world.

## Random Forest Regression

## Performance Metrics of SLR and RFR
