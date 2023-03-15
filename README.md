# LaptopPricePrediction
Laptop Price Prediction using data collected from kaggle
In this project a data analysis is done on the laptop data that is collected from Kaggle Platform. Further to predict price of laptop linear regression and lasso regression is done and to check the accuracy R-squared score is also obtained.
# Process 
STEP 1 - At first the dataset that is obtained is thoroughly analyzed. Different plots are plotted to get a better understanding.

STEP 2 - Data pre-processing is required so certain values of columns where changed further as the dataset had lots of categorical values they were converted to numeric using label encoder library

STEP 3 - While analyzing it was noticed that rating did not affect the price and most of the laptops had the same operating system thus both of these attributes were not affecting the price thus these two were dropped.

STEP 4 - As now the dataset was ready for further analysis at first the target feature was seperated from the rest of the dataset

STEP 5 - Splitting of data into test and train set

STEP 6 - Finally linear and LASSO regression was performed and R-squared value was also measured


