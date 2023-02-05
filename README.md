# Data Analytics Portfolio

**Jessica Tanumihardja**


## [Project 1: Air Quality Regression Analysis with Python from scratch](https://github.com/jtanumihardja/ML-IE7300)

This project is an individual semester-long project for IE 7300 Statistical Learning for Engineering class. The project objective is to design, implement, evaluate, and validate machine learning models using Python programming. The dataset is [The Beijing Air Quality Data](https://archive-beta.ics.uci.edu/ml/datasets/beijing+multi+site+air+quality+data) from the UCI Machine Learning Repository. The business problem to be addressed is training the custom regression models and predicting the target variable values (PM2.5). The objective of this project is to perform statistical analysis on this dataset to find a regression equation to predict the fit and and conclude which regression equation is the best fit for each parameter.

The summary of the performance metrics for each model tested is listed below. The best model is gradient boosting as it has the lowest RSME and highest $R^2$ values. If computational power and time are restricted, lasso regression is also comparable regression model. 

![](/images/AirQualityRegressionResultSummary.png)


## Project 2: Food Delivery Application Database in SQL  

This is a group project consisting 5 people to create a food delivery database using SQL. The purpose of this database is to maintain the data used to support online food ordering and delivery services. The database can be used by the restaurant manager (obtain and track order), delivery person (obtain delivery information), and customer (order and provide ratings). This database serves as a platform to perform contactless business, track orders and perform order analytics. 

The database containes 4 schemas and 15 entities. The Entity Relationship Diagram (ERD) for the database is shown below. Triggers were used to update the user, order, and payment automatically. Column data encryption was used on password to increase security. Computed column procedure was used to calculate payment according to membership level discount automatically. The custom database was tested using 20 restaurants from 4 different US states with at least 3 menu items from each restaurants. SQL Views query were set up for common analytics such as average restaurants rating, top 3 restaurants, and restaurant menus. Vizualizations with PowerBI for those views were also set as shown below. 

**Food Database ERD**

![](/images/FoodDatabase_ERD.png)


**Visualization from PowerBI**

![](/images/FoodDatabase_2.png) 



## Project 3: Boston Craigslist Housing Analysis in R (ongoing)

This individual semester-long project for PPUA 5262 Big Data for Cities class in R. The project objective is to process, analyze, visualize, and model Craigslist's Housing data in Massachusets. The main focus will be in Boston area, turning the big data into products that might benefit communities. Some of the analysis involves housing access, conditions, and equity across Boston’s neighborhoods.



## Project 4: Visualization and Data Analytics in R (ongoing)

This is a group project consisting 4 people for IE6600 Computation and Visualization in R. All the data preprocessing and visualization are conducted in RStudio and the web application is pushed from RShiny. 



## [Project 5: Banana Map (Winner of Northeastern University Hackathon 2023)](https://github.com/jwke21/team_banana_hackathon) 

**Carbon Emission and Energy calculator by various transportation routes**

The Banana Map is a web application that was created for the Northeastern University 2023 Hackathon within 24 hours. The theme for the Hackathon was "Tools of the Future" and our focus wass climate change and environmental sustainability. The objective of our product is to provide incentives and day-to-day comparison for the user on their transportation choice. Transportation is the greatest contributor (~27%) of greenhouse gases emission in the United States. Hence, the first step of heading towards more sustainable life is to wisely choose our transportation option. For this project, we are comparing 4 transportation modes: driving, busing, walking, and cycling. 

For the back-end, we processed the CO2 emission dataset to get the average car mpg (miles per gallon) and CO2 emission (metric tons/mile) in Python. We also gathered resources for energy and calorie calculations. We converted those energy to equivalent number of banana needed so that users can have a tangible comparison (it is also a great source of fuel for our body!). We also showed how much area needed for a forest to sequestered the emitted CO2 (metric tons/area/day). That way, the user will get both biological and environmental comparisons. 

The front-end was built using JavaScript. We were using Mapbox API (open source) to show the map and get the distance between two addresses. The features includes trip distance calculator, CO2 emission tracking, kcal energy expenditure tracking, and equivalent banana calorie tracking. The web interface is shown below. 

Future development of this project includes cross-platform application, user rewards system (getting banana points!), and tracking other carbon saving choices such as household electricity and waste management. 

**Screenshot of web interface**

![](/images/WebInterface_DriveAndWalk.png)

Team Banana: Jake Van Meter, Jessica Tanumihardja, Shreya Goyal, Randy Ramli, Zhiwei Zhou, Chunyun Zhang
