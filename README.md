# The sale of apartments

Project description

I have at my disposal the data of Yandex Real Estate - an archive of ads for the sale of apartments in St. Petersburg and neighboring settlements for several years. I need to learn how to determine the market value of real estate. My task is to set the parameters. This will allow me to build an automated system: it will track anomalies and fraudulent activity.
Two types of data are available for each apartment for sale. The first is entered by the user, the second is automatically obtained on the basis of map data. For example, the distance to the center, the airport, the nearest park and body of water.

My goals are to find:

1. What factors influence the price of an apartment the most? Study whether the price depends on the area, number of rooms, distance from the center. Study whether the price depends on whether the apartment is located on the first floor, the last floor, or another floor. Also, study the dependence on the date of location: day of the week, month and year.

2. Choose the 10 localities with the highest number of listings. Calculate the average price per square meter in these communities. Highlight the localities with the highest and lowest housing costs. This data can be found by the name in the locality_name column.

3. Explore the offers for apartments: for each apartment there is information about the distance to the center. Highlight apartments in St. Petersburg (locality_name). Your task is to find out which area is in the center. Create a column with the distance to the center in kilometers: round up to whole values. Then calculate the average price for each kilometer. Construct a graph: it should show how the price depends on the distance from the center. Determine the boundary where the graph changes a lot - this will be the central area.

4. Identify a segment of the apartments in the center. Analyze the area and study the following parameters: area, price, number of rooms, and ceiling height. Also take into consideration the factors that influence the price of the apartment (number of rooms, floor, distance to the center, the date of the ad). Draw conclusions. Do they differ from the general conclusions of the database?
