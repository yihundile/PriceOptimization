# PriceOptimization

This project develops price optimization machine learning model that helps to maximize profit. The optimization is based on price elasticity of demand, which is the percentage change in quantity demanded when there is a one percent increase in price, holding the remaining factors constant. The model uses cafe data, which was available in three data files. Some of the steps executed in this project included:
-	Merging the dataframes 
-	Making sense out of missing values, and replacing them accordingly 
-	exploring the data to understand the relationship between price and quantity sold. For example, trying to understand the price and quantity relationship for the entire data set vs separating sales for normal days (e.g. excluding sales for weekends, school break days, etc as these sales have different distributions due to different customer buying behavior in these days). Likewise, the price and quantity sold has different relationships for the same item name, but having different sell id.  
-	Fitting linear regression model for different subsets of data, and finding optimal price that maximizes profit 

Overall, developing models by disaggregating the data sales into different subcategories (e.g. excluding weekend, school break days and sales by outdoor or not, id, etc) yielded better model fit. 
