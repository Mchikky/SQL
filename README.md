# Project 3: SQL - Creation and use of real estate database

## Objective:
Create a real estate database using MySQL and query the database to retrieve some information.

## Mission:
- Prepare a data dictionnary showing the codes, description, type and length of codes.
- Design a schema showing relationships, entities and cardinalities of the database.
- Query the database to answer some questions on the sales of houses and appartments.

## Data source
OpenClassrooms: 3 Excel documents

## Data preparation
- Normalize data observing the 3 normal forms
  1. 1NF- removes repeated groups from a table to gurantee atomicity,
  2. 2NF- Lessens redundancy by eliminating partial redundancies
  3. 3NF- Reduces data duplication by removing transitive dependancies
- Identify primary key, secondary key, remove duplicates, eliminate redundant data, isolate relationships using database normalization
- Categorize data into 3 excel spreadsheets: bien (property), sales (ventes), and commune (city)
- Link tables through primary key and secondary keys using HLOOKUP function in Excel
- Import the database into MySQL using reverse engineering

## Data analysis
1. Total number of appartments sold in the first quarter of 2020.
2. Proportion of appartment sold by number of rooms
3. List of 10 departments where the price of square metre is the most expensive
4. Price of an average square metre of houses in Ile de France
5. List of the 10 most expensive appartments, their departments and number of square metres
6. Rate of change in sales figures between first and second quarter in 2020
7. List of cities where the number of sales increased at least 20% between first and second quarter of 2020
8. Difference in price percentage of square metre between an appartment of 2 rooms and an appartment of 3 rooms
9. Average value of property for the 3 top cities in departments 6, 13, 33, 59 and 69.

## Insights
1. Total number of appartment sold in the first quarter of 2020 is 30897
2. 2 room apartment is the highest sold
3. Price of a square metre is highest in department 75
4. Average price of square metre of a house in Ile de France is approximately 5231
5. The most expensive appartment is found in department 75
6. Rate of change in sales figure is approximately 3.7%
7. Average value of property is highest in Nice based on the departments 6, 13, 33, 59 and 69 selected.
   
## Recommendations
- The real estate company should invest more in the construction of 2 room apartments since they sell faster than other types.
- More advertisement is needed to boost sales figures in subsequent years.
- For better Return on Investment (ROI) on properties, there is need to check the prices of appartments and houses in other departments.
