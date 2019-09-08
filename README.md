## Multiple Regression Analysis Using Airbnb Data

The objective of this project is to make onboarding process for Boston homeowners easier by suggesting to them how much they should charge for their property.

The dataset is from Airbnb, which includes about 37 features and 3,586 observations. To give an overview of this data, some features are the following:
- neighbourhood
- property type
- room type
- bed type
- amenities
- reviews rating

This project is done using R and I will follow Google's R style guide.

### Analysis 1
#### What causes the diffence between prices in listings?
*Data Wrangling*: Please see the following [data](https://github.com/gpadolina/multipleRegressionAnaysisWithAirbnb/blob/master/priceModel.R) transformation that I made by leveraging dplyr and tidyr libraries using R. I will use the cleaned data for the rest of the analysis.

Here, I categorized the listings based on their room type.

| Room Type | Frequency |
| --- | --- |
| Entire home/apt | 2127 |
| Private room | 1378 |
| Shared room | 80 |

![Image of Room Type](https://github.com/gpadolina/multipleRegressionAnaysisWithAirbnb/blob/master/plots/roomType.png)

