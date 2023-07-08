## Housing Sale Price Analysis in King County, WA
### Business Understanding

My Space Agency serves the King County community by providing prospective home sellers with guidance on how to improve the value of their home before listing for sale.
Business Problem:

    The Agency's primary aim is to provide prospective home sellers with guidance on how to improve the value of their home prior to listing, including the predicted increase in value expected based on improvements to particular features.

Business Question:

    What features of their home can prospective home sellers change or improve to increase the value of their home, and how much could this increase be specific to certain features? These recommendations derived from this report would be valuable to My Space Agency Realtors because it would help prospective home sellers confidently ascertain how they can improve the value of their home, and if the investment is worth the cost.

### Data Understanding

This project uses the King County House Sales dataset because My Space Agency and its prospective homesellers are all based in King County. The dataset itself can be found in kc_house_data.csv in the data folder of this GitHub repository along with the descriptions of the features, found in column_names.md.

The original dataset includes sales data for 21,597 homes with 20 different features, which include:

    - date - Date house was sold
    - price - Sale price (prediction target)
    - bedrooms - Number of bedrooms
    - bathrooms - Number of bathrooms
    - sqft_living - Square footage of living space in the home
    - sqft_lot - Square footage of the lot
    - floors - Number of floors (levels) in house
    - waterfront - Whether the house is on a waterfront
    - view - Quality of view from house
    - condition - How good the overall condition of the house is. Related to maintenance of house
    - grade - Overall grade of the house. Related to the construction and design of the house
    - sqft_above - Square footage of house apart from basement
    - sqft_basement - Square footage of the basement
    - yr_built - Year when house was built
    - yr_renovated - Year when house was renovated
    - zipcode - ZIP Code used by the United States Postal Service
### Data Processing
To assist with creating sound models, we completed some data cleaning including:

    - Dropping unrelated features to our business question (ID, sale date, zipcode, latitude, longitude, year renovated, view, lot size, and the lot size and living space of a home's 15 closest neighbords)
    - We also checked and dropped outliers for price and bedrooms.
### Modeling
We are showing correlation and using regression coefficients in this analysis to be able to show the relationship between one or more features with sale price.

Using regression and interpreting correlation coefficients is effective for this business problem because it will allow for us to determine how sale price is impacted by different features and to what degree.

Buildng complex models with multiple features allows for us to be able to make more accurate, data-driven predictions.

