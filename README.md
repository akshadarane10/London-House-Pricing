# London-House-Pricing
Data Cleaning, Data Transformation, Data Modelling, Data Visualization

# End to End Process: [Cleaning, Data transformation, Data Modelling & Data Visualization
-	Data: LondonHousePrices
-	We had Borough names as column header & dates as row in our initial data frame - properties
-	We transposed this data & formatted it using melt 
-	We got Boroughs, dates & their values in a dataframe
-	Then kept only the required Boroughs in the dataframe (removed nonBoroughs from the dataframe)
-	Extracted the Year column from Date column
-	Removed the null values
-	We then used groupby (borough & Year) to calculate the average price of each borough 
-	We then made a function that calculate the ratio to compare, 1999 prices to 2018 prices
-	Then we created the dataframe df1_ratios, containing Boroughs & ratios
-	Then plotted a bar graph containing highest ratios, high growth in prices

# Insights:
-	During our 1st line graph – for only Camden Borough, we saw that it had increasing trend for its average price through out the period from 1999 – 2015, then the prices are pretty stagnant till 2024
o	Similar plots can be observed for other boroughs too by selecting the required borough in the dropdown
 
-	Top 15 Boroughs are, highest growth in house prices in last 2 decades
o	Text(0, 0, 'Hackney'),
o	 Text(1, 0, 'Waltham Forest'),
o	 Text(2, 0, 'Southwark'),
o	 Text(3, 0, 'Lewisham'),
o	 Text(4, 0, 'Westminster'),
o	 Text(5, 0, 'Newham'),
o	 Text(6, 0, 'City of London'),
o	 Text(7, 0, 'Haringey'),
o	 Text(8, 0, 'Kensington & Chelsea'),
o	 Text(9, 0, 'Lambeth'),
o	 Text(10, 0, 'Camden'),
o	 Text(11, 0, 'Barking & Dagenham'),
o	 Text(12, 0, 'Brent'),
o	 Text(13, 0, 'Islington'),
o	 Text(14, 0, 'Greenwich')]

-	the lowest 15 are
o	Text(0, 0, 'Hounslow'),
o	Text(1, 0, 'Richmond upon Thames'),
o	Text(2, 0, 'Harrow'),
o	Text(3, 0, 'Bromley'),
o	Text(4, 0, 'Sutton'),
o	Text(5, 0, 'Hammersmith & Fulham')                        , 
o	Text(6, 0, 'Hillingdon'),
o	Text(7, 0, 'Croydon'),
o	Text(8, 0, 'Bexley'), 
o	Text(9, 0, 'Enfield'),
o	Text(10, 0, 'Kingston upon Thames'),
o	Text(11, 0, 'Ealing'),
o	Text(12, 0, 'Havering'),
o	Text(13, 0, 'Barnet'),
o	Text(14, 0, 'Redbridge')                                                       

-	

