# Syracuse-Housing-Database---Database-Management-Systems

## Project Summary:

In order to buy, rent or sell the property, customers have to rely on the property dealers for getting them the best prices or visit different websites, which in turn affects their decisions. However, all these do not provide them on the spot comparison or user reviews. Even student face a hard time while finding apartments if they are coming to a new country or city for studies. The proposed Information system would be a database, where the customers will be able to view property. The suggested database will include information about houses, localities, landlords, user reviews and comparison of various property retail websites. Since everything is online these days, it will turn out to be an easy option for the customers as it will save time and money. This would give the customer all the potential houses along with the prices offered by different websites and amenities present in the apartment. The target audience would be people who are potential buyers and leasers, viewing property for future transactions.

## Business Rules:
All the property retail websites are limited to Syracuse.
The value of the property is in terms of dollars.
Every property must have only one landlord.
A landlord can own zero or multiple properties.
Every property retail website has at least one property to display.

## Entities:
1)	Users – Different type of users like students and buyers who view the property
2)	Student – Students who view the property for leasing in the future
3)	Buyer – Students who view the property for leasing in the future
4)	Landlord – People who own the property(Owner/Landlord)
5)	Property – Types of property and its description (Rental or Property for Sale)
6)	Rental Property – Details regarding the Rental Property and lease of the property
7)	PropertyForSale – Details regarding the Rental Property and lease of the property
8)	Feature – Details about various features of the property
9)	FeatureDesc – Detailed Description about the Feature name
10)	RetailWebsite – Details regarding different Websites
11)	Display – Associative entity between RetailWebsite and Property to show the details about the property on a particular website
12)	Review – Details regarding the review of the property

## Database Infrastructure:
The database system infrastructure used is based on a client-server model. SQL Server is used as the database engine and Access is used as the interface design tool. Data is inserted, deleted, updated, and queried from the SQL Server database with the help of forms on Access. Useful data stored on the SQL Server database can also be viewed with the help of reports generated through Access.

## Business Questions:
1) What percentage of users are students and buyers
2) What percentage of Users are male and female
3) What is the age range of students
4) What perentage of properties does each website display?
5) What is the average rating of each website
6) What percentage of property is for renting and buying
7) What are the total number of rental properties in different rent range
8) What are the total number of sale properties in different price range
9) Which is most expensive Rental property and Property for Sale in the entire database
10) Which is least expensive expensive Rental property and Property for Sale in the entire database
11) What is the street wise rating of different Rental properties and how many rental properties are there on a single street
12) What is the street wise rating of different Sale properties and how many Sale properties are there on a single street
13) Which feature is present in most houses
14) What are the total number of distinct features present in all the properties



