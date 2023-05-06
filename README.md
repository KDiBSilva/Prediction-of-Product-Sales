# Prediction of Product Sales

### Analyzing Correlations for Product Sales Predictions
Kristina DiBella Silva

**There are multiple variables to consider for sales prediction. In this exploration we look at the data from Item specification to Store location details, which tell us the correlation the have is producing the highest sales.**
___

### Data Source
https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view?usp=sharing

For this dataset, there were 8523 rows and 12 columns.

### Data Dictionary
![image](https://user-images.githubusercontent.com/122838459/236369360-86ccda50-ada1-4fc2-b2db-a3ead9dfc68a.png)

___

#### To prepare this data, the data was cleaned and the following processes were performed:

## Exploratory Data Analysis

- To explore the dataset, a boxplot and histogram were used to visualize each column with numerical datatypes.
- For categorical columns, a barplot was used for visualization. 
- These univariate plots provided a good interpretation for both numeric and categorical datatype columns.

![hist sales](https://user-images.githubusercontent.com/122838459/236587354-c7522e5c-186d-4870-88c6-d68896b57e77.png)

This histogram shows that the majority of outlet sales per item produced ₹3,500 and under. 
Recognizing the skew of outliers to the right produce ₹9,500 and more. 

![cnt product](https://user-images.githubusercontent.com/122838459/236588557-cd928c35-9fc1-40a9-a52d-fbc216665be4.png)


The item type's with the larges category count are as follows:
  1. Fruits and Vegetables
  2. Snack Foods  
  3. Household
  4. Frozen Food

The item type's with the smallest category count are as follows:
  1. Seafood
  2. Breakfast 
  3. Starchy Foods
  4. Hard Drinks 

___

## Explanatory Data Analysis
- To demonstrate the data for explanatory purposes, two barplots and a scatterplot were used.
- The multivariant scatterplot was used to see the correlation between two numerical values. 
- The barplots were used to observ the a categorical datatype relationt to Item Outlet Sales.

![explanscatt](https://user-images.githubusercontent.com/122838459/236588981-ac4df13d-bdb1-4c00-9d3c-a3b2f8b56057.png)

The scatterplot above shows the moderate correlation of Item Outlet Sales and Item MRP.

![explanbar1](https://user-images.githubusercontent.com/122838459/236589046-ba74fe68-a1b6-4d50-a410-0980e79371eb.png)

In this barplot we can determine the top five item types with the highest sales.
  - Seafood
  - Starchy Foods
  - Breakfast
  - Bread
  - Fuits and Vegetables

![explanbar2](https://user-images.githubusercontent.com/122838459/236589058-d6c47683-081b-444f-9d62-604489a93a3f.png)

For this multiplot we see that the Tier 1 type location performs the least in Item Outlet Sales and Grocery Store outlet type provides the least in Item Outlet Sales.
Supermarket Type 3 has contributed to the highest from the the other three outlet types. AS for the location types, Tier's 2 and 3 perduce the highest amount of sales with Tier 2 being slightly higher.
___

## Machine Learning Using the Following Models:
- Linear Regression Model
- Lasso Model, L1
- Decision Tree Regressor Model

### Models Evaluated & Results

## Recommenations
