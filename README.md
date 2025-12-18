# real_estate_price_prediction
Created a simple real estate price predictor using california housing dataset and RandomForestRegressor model
1.In the first five cells i have loaded the dataset and got information about the dataset like the non null counts and mean,median,min,max
2.In the sixth cell , I have inspected the target variable distribution using histogram
3.In the seventh cell, each feature has been plotted with box plot to see the outliers without including the lattitude and longitude(since it is a real estate house prediction model , the outliers gives information of high price houses and high populated area, so outliers dont contribute big in loss)
4.In the nineth cell , I have scaled each feature using standardscaler to make the data centered 
5.In the eleventh cell, the data has been splitted using train_test_split with 20% of test data
6.Using Linear Regression model , got root mean squared error 0.74
7.Using RandomForestRegressor , got root mean squared error 0.50
