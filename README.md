# House Price Prediction in India using Linear Regression
This Repository helps to build a machine learning model to predict house prices in India using Linear Regression.

## Process of building any model

To build a machine learning model to predict house prices in India using linear regression, we will follow these steps:
<ol>
<li>Load the Data</li>
<li>Explore and Preprocess the Data</li>
<li>Split the Data into Training and Testing Sets</li>
<li>Build the Linear Regression Model</li>
<li>Train the Model</li>
<li>Evaluate the Model</li>
<li>Visualize the Results</li></ol>

## Dataset
The dataset is extracted from Kaggle - <a href="https://www.kaggle.com/datasets/mohamedafsal007/house-price-dataset-of-india?resource=download">House Price Dataset</a>

This dataset contains information about house prices in India with various features such as the number of bedrooms, bathrooms, living area, lot area, etc.<br>
This data Set contains 23 columns and 14620 Rows.

## Dataset Columns

The dataset contains the following columns:

- `id`
- `Date`
- `number of bedrooms`
- `number of bathrooms`
- `living area`
- `lot area`
- `number of floors`
- `waterfront present`
- `number of views`
- `condition of the house`
- `grade of the house`
- `Area of the house from basement`
- `Basement area`
- `Built Year`
- `Renovation Year`
- `Postal Code`
- `Lattitude`
- `Longitude`
- `living_area_renov`
- `lot_area_renov`
- `Number of schools nearby`
- `Distance from the airport`
- `Price`


## Summary Statistics

- **number of bedrooms**: Ranges from 0 to 33, with a mean of 3.4.
- **number of bathrooms**: Ranges from 0 to 8, with a mean of 2.1.
- **living area**: Ranges from 290 to 9410, with a mean of 2080.
- **lot area**: Ranges from 651 to 1,074,214, with a mean of 15,112.
- **number of floors**: Ranges from 1 to 3.5, with a mean of 1.5.
- **waterfront present**: Binary variable (0 or 1).
- **number of views**: Ranges from 0 to 4, with a mean of 0.6.
- **condition of the house**: Ranges from 1 to 5, with a mean of 3.4.
- **grade of the house**: Ranges from 1 to 13, with a mean of 7.7.
- **Area of the house (excluding basement)**: Ranges from 290 to 9410, with a mean of 1986.
- **Area of the basement**: Ranges from 0 to 4820, with a mean of 291.
- **Built Year**: Ranges from 1900 to 2015, with a mean of 1971.
- **Renovation Year**: Ranges from 0 to 2015, with a mean of 90.9.
- **Postal Code**: Ranges from 122003 to 122072, with a mean of 122033.
- **Lattitude**: Ranges from 52.3859 to 53.0076, with a mean of 52.8.
- **Longitude**: Ranges from -114.709 to -113.505, with a mean of -114.4.
- **living_area_renov**: Ranges from 460 to 6110, with a mean of 1996.
- **lot_area_renov**: Ranges from 651 to 560,617, with a mean of 12,753.
- **Number of schools nearby**: Ranges from 1 to 3, with a mean of 2.
- **Distance from the airport**: Ranges from 50 to 80, with a mean of 65.
- **Price**: Ranges from 78,000 to 7,700,000, with a mean of 538,932.

At the end, the dataset contains the-
- **Training set**: 11,696 samples
- **Testing set**: 2,924 samples

