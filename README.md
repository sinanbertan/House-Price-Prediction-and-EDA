
# House Price Prediction and EDA

- This repository contains the code and data for a project on house price prediction and exploratory data analysis (EDA). The project uses the house_price dataset, which can be downloaded from Kaggle.


## Data Source

- Data fields
Here's a brief version of what you'll find in the data description file.

- SalePrice - the property's sale price in dollars. This is the target variable that you're trying to predict.
- MSSubClass: The building class
- MSZoning: The general zoning classification
- LotFrontage: Linear feet of street connected to property
- LotArea: Lot size in square feet
- Street: Type of road access
- Alley: Type of alley access
- LotShape: General shape of property
- LandContour: Flatness of the property
- Utilities: Type of utilities available
- LotConfig: Lot configuration
- LandSlope: Slope of property
- Neighborhood: Physical locations within Ames city limits
- Condition1: Proximity to main road or railroad
- Condition2: Proximity to main road or railroad (if a second is present)
- BldgType: Type of dwelling
- HouseStyle: Style of dwelling
- OverallQual: Overall material and finish quality
- OverallCond: Overall condition rating
- YearBuilt: Original construction date
- YearRemodAdd: Remodel date
- RoofStyle: Type of roof
- RoofMatl: Roof material
- Exterior1st: Exterior covering on house
- Exterior2nd: Exterior covering on house (if more than one material)
- MasVnrType: Masonry veneer type
- MasVnrArea: Masonry veneer area in square feet
- ExterQual: Exterior material quality
- ExterCond: Present condition of the material on the exterior
- Foundation: Type of foundation
- BsmtQual: Height of the basement
- BsmtCond: General condition of the basement
- BsmtExposure: Walkout or garden level basement walls
- BsmtFinType1: Quality of basement finished area
- BsmtFinSF1: Type 1 finished square feet
- BsmtFinType2: Quality of second finished area (if present)
- BsmtFinSF2: Type 2 finished square feet
- BsmtUnfSF: Unfinished square feet of basement area
- TotalBsmtSF: Total square feet of basement area
- Heating: Type of heating
- HeatingQC: Heating quality and condition
- CentralAir: Central air conditioning
- Electrical: Electrical system
- 1stFlrSF: First Floor square feet
- 2ndFlrSF: Second floor square feet
- LowQualFinSF: Low quality finished square feet (all floors)
- GrLivArea: Above grade (ground) living area square feet
- BsmtFullBath: Basement full bathrooms
- BsmtHalfBath: Basement half bathrooms
- FullBath: Full bathrooms above grade
- HalfBath: Half baths above grade
- Bedroom: Number of bedrooms above basement level
- Kitchen: Number of kitchens
- KitchenQual: Kitchen quality
- TotRmsAbvGrd: Total rooms above grade (does not include bathrooms)
- Functional: Home functionality rating
- Fireplaces: Number of fireplaces
- FireplaceQu: Fireplace quality
- GarageType: Garage location
- GarageYrBlt: Year garage was built
- GarageFinish: Interior finish of the garage
- GarageCars: Size of garage in car capacity
- GarageArea: Size of garage in square feet
- GarageQual: Garage quality
- GarageCond: Garage condition
- PavedDrive: Paved driveway
- WoodDeckSF: Wood deck area in square feet
- OpenPorchSF: Open porch area in square feet
- EnclosedPorch: Enclosed porch area in square feet
- 3SsnPorch: Three season porch area in square feet
- ScreenPorch: Screen porch area in square feet
- PoolArea: Pool area in square feet
- PoolQC: Pool quality
- Fence: Fence quality
- MiscFeature: Miscellaneous feature not covered in other categories
- MiscVal: $Value of miscellaneous feature
- MoSold: Month Sold
- YrSold: Year Sold
- SaleType: Type of sale
- SaleCondition: Condition of sale
- (https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data?select=train.csv)



## Installation
The following tools were used for this analysis:

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Sklearn

- To run this project, you will need to have Python 3 installed on your machine. You can install the required libraries by running the following command:


- pip install pandas matplotlib seaborn numpy plotly

    
## Usage 
- To run the analysis, simply execute the notebook. The script will generate several visualizations that help illustrate analysis of data.
## Roadmap

The analysis includes the following tasks:

- Data loading and cleaning
- Exploratory data analysis
- Feature engineering
- Correlation analysis
- detecting outliers
- building model 

The analysis includes visualizations using Matplotlib, Plotly and Seaborn.

## Result

- In this project, we conducted exploratory analysis and price prediction on the "house_price.csv" dataset. The dataset provided a comprehensive set of features related to residential properties, allowing us to gain insights into the factors influencing house prices.

- We performed data preprocessing steps, including handling missing values, removing outliers, and encoding categorical variables.

-  we identified several numerical and categorical features that showed strong correlations with the target variable. These features included "OverallQual," "GrLivArea," "GarageCars," and "Neighborhood," among others.

- For price prediction, we employed various regression algorithms, including linear regression, decision tree regression, and random forest regression. After thorough evaluation and comparison of the models using appropriate metrics such as Root-mean-square deviation (RMSE) and R-squared, we found that the random Gradient Boosting Regression model outperformed the other models, providing the highest accuracy in predicting house prices.

- Our analysis also highlighted the significance of certain features in determining house prices. For instance, the overall quality of a property, the living area, and the number of cars that can be accommodated in the garage played crucial roles in determining the sale price.

- In conclusion, through our analysis of the "house_price.csv" dataset, we successfully explored and predicted house prices using regression techniques. Our findings provide valuable insights for homeowners, real estate agents, and potential buyers to understand the factors that influence house prices. Future research could focus on incorporating additional external datasets, such as economic indicators and neighborhood amenities, to further enhance the accuracy of price predictions.
## Contributing

- Contributions to this project are welcome. If you notice any errors or have ideas for additional analyses, please feel free to open an issue or submit a pull request.


## License
[MIT](https://choosealicense.com/licenses/mit/)
- This project is licensed under the MIT License - see the LICENSE file for details.


