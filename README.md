# RentalPricingExplore


## Project Intro/Objective
The purpose of this project is to extract an analysis of rental properties in Taipei City provided by a real estate company. We are to determine how much the real estate company should charge for their properties. 

### Methods Used
* Inferential Statistics
* Machine Learning
* Data Visualization
* Predictive Modeling
* etc.

### Technologies
* R 
* Python
* D3
* PostGres, MySql
* Pandas, jupyter
* HTML
* JavaScript
* etc. 

## Project Description

We were given a dataset provided by a real estate company to "clean" up errors and to extract an analysis of rental properties. The dataset contained various information of each property. To the houses age, location and the price of the units area. It also provided the number of convenience stores and the distance to the nearest MRT station. 

![Scatter Plot](https://github.com/MichaelJCanales/RentalPricingExplore/blob/07e9f09e0c6f41d999a99c73635a7fde37465e21/docs/images/Scatter%20Plot%20of%20Distance%20to%20the%20Nearest%20MRT%20vs%20Price%20per%20Unit%20Area.png)

We use the data to see how it will influence the rental housing prices. We explored the distribution of the variables in the dataset and plotted histograms, scatter plots, and a heatmap to visualize the data. To predict the rental housing prices we'll use a linear regression model to  evaluate and to explain and assess the rental prices. 


### Challenges 
* Numeric column interpreted as a string
* Column not relevant to the analysis
* Rows with missing values 
* Long column names
* Unknown units (distance , currency)  
