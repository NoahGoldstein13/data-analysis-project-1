# Data Analysis Project 1 - How have vehicles changed over the past 2.5 decades?
----------

## Background
----------
Our team was tasked with exploring a question of interest through detailed analysis. We ultimately decided to explore how cars have changed over time and through analyzing highway mpg, price, weight, and technology for three distinct body styles/types (cars, trucks, vans).

## Tools and Technology Used for Analysis
----------
* CSVs
* Pandas
* Matplotlib
* Numpy
* VSCode
* Scipy
* Jupyter Notebook
* Google Slides

## Data Source
----------
1. Our datasource was found on reddit https://www.reddit.com/r/datasets/comments/b6rcwv/i_scraped_32000_cars_including_the_price_and_115/
2. The datasource contains information on 32,000 vehicles and 115 specifications. We decided to analyze some of these specifications including Retail Price (MSRP), Gas Mileage, Body Style (Cars, Trucks, Vans), Base Curb Weight (lbs) and Technology (Stability Control, Backup Cameras, Parking Aids).


## How to Ingest the Completed Project
----------
1. Save the cleansed car data file ("car_data.csv") to a folder called "Clean_data"
2. Save the code in the "complete_data_analysis_code.ipynb" to an ".ipynb"
3. Create a blank folder called "output_images" for the output analysis charts
4. Run the code in jupyter notebook
5. You will now see the analysis in your jupyter notebook and the chart outputs in your "output_images" folder.

## Summary of Findings
----------
How cars have changed for consumers from 1996 to 2019 based on common car specifications?

1. On average, cars have become steadily more expensive over time
2. On average, gas mileage has improved over time despite a drop in effiency in 2008
3. On average, cars have become heavier over time, despite a drop in average weight in 1998

What is the relationship between car specifications for three vehicle styles (cars, trucks, vans)?

Retail Price vs Weight

1. Retail price has increased for cars, trucks and vans over the last 23 years
2. There is a strong correlation between the weight of cars and their price
3. There is not a strong correlation between the weight of vans and their price
4. There is not a strong correlation between the weight of trucks and their price

Retail Price vs MPG

1. Highway Miles Per Gallon (MPG) has improved for cars, trucks and vans over the last 23 years
2. There is a moderate to strong positive correlation between the price of cars and their highway MPG
3. There is a moderate positive correlation between the price of vans and their highway MPG
4. There is a moderate positive correlation between the price of trucks and their highway MPG

Weight vs MPG

1. The weight of cars and trucks has increased over time and remained consistent for vans over the last 23 years
2. There is a weak negative correlation between the weight of trucks and their MPG
3. There is a weak negative correlation between the weight of vans and their MPG
4. There is a strong negative correlation between the weight of cars and their MPG. A decrease in weight is correlated with an increase in MPG.

Technology in Vehicles

1. Stability control is one of the earliest technologies in vehicles (since 1996) and has been added to more vehicles over time
2. Backup cameras were added to cars in 1997 and continue to be added to more vehicles over time
3. Parking aids were incorporated into vehicles in 2003 and have steadily been incorporated in more cars over time. 
