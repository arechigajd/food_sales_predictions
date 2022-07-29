# Sale Prediction Project
# Overview
  The purpose of this project was to take data from a store outlet and see if we could use that data to predict future sales of it's items.
# Insights
  There is positive correlation between Item_MRP and Outlet_sales, while there is negative correlation between Item_visibility and Outlet_Sales.
  ![image](https://user-images.githubusercontent.com/106642637/181708699-7e5a4298-aa83-4783-ad69-08e88afa67cb.png)
  
  The distribution of Item_MRP gives an idea of the prices of the items being sold and the store outlets.
  ![image](https://user-images.githubusercontent.com/106642637/181709303-45c49ab6-dadd-446d-8e04-d5122fdd8678.png)
# Summary of Models
  There is a linear regression model and a regression tree model. The model with better performance is the regression tree model. This is backed up by the higher R2 metric scores and by the smaller gap in the RMSE metric scores. The scores given to the regression tree model show a better balance out of the two models.
# Final Recommendation
  The regression tree model should be implemented for best results. It will yeild the best possible predictions for future sales.
