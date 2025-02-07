# California Housing Price Prediction
<br>
This repo explores various techniques to build an effective model for predicting housing prices based on available attributes in the California housing dataset. The goal is to create a model that can accurately estimate house prices by utilizing data preprocessing, feature engineering, and model training.
<br>

> ## California Housing Dataset
> 
> **Data Set Characteristics:**
> 
> - **Number of Instances:** 20,640  
> - **Number of Attributes:** 8 numeric, predictive attributes and the target  
> 
> **Attribute Information:**
> 
> - **MedInc**: Median income in block group  
> - **HouseAge**: Median house age in block group  
> - **AveRooms**: Average number of rooms per household  
> - **AveBedrms**: Average number of bedrooms per household  
> - **Population**: Block group population  
> - **AveOccup**: Average number of household members  
> - **Latitude**: Block group latitude  
> - **Longitude**: Block group longitude  
> 
> **Missing Attribute Values:** None  
> 
> This dataset was obtained from the [StatLib repository](https://www.dcc.fc.up.pt/~ltorgo/Regression/cal_housing.html).
> 
> The target variable is the median house value for California districts, expressed in hundreds of thousands of dollars ($100,000).
> 
> This dataset was derived from the 1990 U.S. Census, using one row per census block group. A block group is the smallest geographical unit for which the U.S. Census Bureau publishes sample data (a block group typically has a population of 600 to 3,000 people).
> 
> A household is a group of people residing within a home. Since the average number of rooms and bedrooms in this dataset are provided per household, these columns may take surprisingly large values for block groups with few households and many empty houses, such as vacation resorts.
> 
> It can be downloaded/loaded using the `sklearn.datasets.fetch_california_housing` function.
> 
> **References:**
> - Pace, R. Kelley and Ronald Barry, *Sparse Spatial Autoregressions*, Statistics and Probability Letters, 33 (1997) 291-297.

  
## To run locally

```bash
git clone git@github.com:janneheldan/house-price-prediction-ml.git
cd house-price-prediction-ml
```
<br>

```bash
pip install -r requirements.txt
```
<br>

```bash
jupyter lab house_price_prediction.ipynb
```
