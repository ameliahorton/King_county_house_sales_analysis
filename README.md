# House Sales in King County, USA

## Project Description
The House Sales in King County, USA dataset contains house sale prices for King County, which includes Seattle from May 2014 to May 2015. It will be used to determine if certain house features have an effect on the price of house sales.
 
![house](images/house.png)

## Process

![process](images/process.png)


## Research Question
Do house features have an effect on the price of house sales?


## House Features
*	Bedrooms & bathrooms
*	Sq_ft living
*	Zipcode
*	Waterfront view
*	Year house was built


## Hypothesis
House features do have an effect on the price of house sales.


## Bedrooms & Bathrooms

The average amount of bedrooms and bathrooms is 3 bedrooms and 2.11 bathrooms.

### Is the price higher when there are more bedrooms or bathrooms?

Price is higher for houses with more bedrooms or bathrooms, but only to a certain extent as shown in the scatter plots: “Bedrooms vs. Price” and “Bathrooms vs. Price” and bar graphs: “Average Price by Bedrooms Bar Graph” and “Average Price by Bathrooms Bar Graph” and as indicated by the r-squared value, which describes the correlation between the bedrooms and price and bathrooms and price. 

Since the r-squared value for bedrooms and price is 0.308, there’s a weak correlation between the amount of bedrooms and price. Also, the outliers of 11 and 33 bedrooms sold at $520,000 and $640,000 emphasizes that not all houses with many bedrooms have a high price since these 2 sold houses have the most bedrooms in this dataset, but they weren’t sold at the highest price. 

![Bedrooms vs. Price](output_data/Bedrooms%20vs.%20Price.png)

On the other hand, since the r-squared value for bathrooms and price is 0.525, there’s a moderate correlation between the amount of bathrooms and price.

![Bathrooms vs. Price](output_data/Bathrooms%20vs.%20Price.png)


## Sqft_living

### What’s the correlation between sqft_living and pricing? 

The data shows that there is a strong positive correlation between the square footage of a home and its price. As homes increase in square feet, the house price increases. 
![Square Footage vs. Price](output_data/Square_Footage%20vs.%20Price.png)


## Zipcode

### Are house sale prices higher in higher income neighborhoods?
In general, there is little correlation between house price and household income. Lower home prices exist in every neighborhood, and higher ones are scattered throughout. One thing I did notice is that very high income zips have a slightly greater spread in home prices, between 0 and 3 million, while lower income zips mostly have homes between 0 and 1 million. The highest home price in the whole dataset is in a middle-income zip. The top ten most expensive homes usually exist in zips with higher average home prices, but not always. I noticed that these ten homes are only in six different zip codes, meaning that many of those zips contain multiple of the top ten homes. This does show some concentration of expensive houses in certain areas, but other expensive homes are in areas with lower average prices.

## Waterfront view

### Do houses with a waterfront view or without a waterfront view have more price outliers?
Within the same living square footage range, price is higher for houses having waterfront view than non-waterfront view. King county's house dataset showed houses with the same bedrooms, waterfront view properties are definately having higher price point than non-waterfront. 

Barchart: waterfront vs nonwf price shows price comparision within same living square footage which waterfront is higher.

Scatterchart: Waterfront Bedrooms vs. Prices clearly shows for houses having the same bedrooms, prices are higher for those having waterfront view.

Boxplot: Waterfront(Non-waterfront) vs. Price shows median, upper quartile, lower quartile, upper extreme and lower extreme for both waterfront and non-waterfront houses.

![ Waterfront(Non-waterfront) vs  Price boxplot](https://user-images.githubusercontent.com/100645924/164571054-b790abab-b7f1-405a-9878-e80b6b42defa.png)


### Do larger sqft_living greater than 6,000 sqft with a waterfront view cost more or less than those without a waterfront view?

For houses over 6,000 sqft, there is a significant difference in price. On average, these larger houses with a waterfront cost about 2.5 million dollars more than those without a waterfront. 

![Average Prices of Homes Greater than 6,000 sqft with and without Waterfronts vs. Price](output_data/Average%20Prices%20of%20Homes%20Greater%20than%206,000%20sqft%20with%20and%20without%20Waterfronts.png)

## Year house was built

### Do newly built homes cost more than older built homes and where/ which zipcodes are the majority of the newly built homes located at?

According to the plots below, newly built homes do not cost more than older homes in general. However there seems to be a stronger correlation between price and home if it has been renovated. This could be due to fewer data points in the year renovated plot (only 4.2% of the homes have been renovated).

![Year Built vs. Price](output_data/yearbuiltvsprice.png)

![Year Renovated vs. Price](output_data/yearrenovatedvsprice.png)

### Neighborhoods with newest houses

Central Seattle Area:
*98103 Greenlake
*98115 Ravenna/Maple Leaf
*98144 Atlantic/Mt. Baker

A bit further out:
*98040 Mercer Island
*98056 Renton

![Map of Newest Homes](output_data/topsixnewhouses.png)

