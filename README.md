# Sales Prediction Model
## Machine Learning Sales (Revenue $) Prediction Model 

**Author: Thomas Greenacre**: 

### Business problem:

To create a model that accurately predicts Sales based on historical data and machine learning techniques


### Data:
Source: sales_predictions (1).csv

Descitpion: Data set that has sales (Item_Outlet_Sales) by item with a number of features including Item_MRP, Item_Visibility, Outlet_Size, etc.


## Methods (Data preparation steps)
- check & remove (if needed) duplicate rows
- Checking & address any missing data
- cleaned any fields where approapriate to solve for similar value naming conventions
- nomininal encoded mean values for missing data on features with numeric (int, float) data type
- OneHot encoded the most frequent values for missing data on features with object data type

## Results

#### Feature Correlation Heatmap

![image](https://user-images.githubusercontent.com/104700955/176902787-08c2a6eb-a7b2-472b-8fd1-f377b33a294d.png)

> this visual shows the relationship (correlation) between the different features in the dataset

#### Item MRP Box Plot

![image](https://user-images.githubusercontent.com/104700955/176902544-9e3ea546-06c6-4185-8a5e-e69b741bd91b.png)

this visual shows the range of values for the Item MRP feature represented by a Box Plot

## Model

The final model(s) tested to predict the Sales (Item_Outlet_Sales) are 1 Linear Regression model and 1 Decision Tree model.

The most important metric is the R-Squared (R2) which was used to evaulate how well the models would accurately predict Sales (Item_Outlet_Sales)

Additinal metric used to evaluate the models was the Root Mean Squared Error (RMSE)

## Recommendations:

Based on the R2 scores used to evaluate both models (see below); the Decision Tree Model should be impletemented

Linear Regression R2 Scores
*   Train: 0.560543
*   Test: 0.565847

Decisions Tree R2 Scores
*   Train: 0.603925
*   Test: 0.594747


## Limitations & Next Steps

Both models coulds be improved with more data and/or features. Next step to improve the data set used and re-run prediction models to improve overal R2 scores.


### For further information


For any additional questions, please contact **thomas.greenacre@gmail.com**
