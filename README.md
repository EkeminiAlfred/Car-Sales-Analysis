# Sales Analysis of Different Car Brands
 
 #### Introduction
 
##### Objective: 

As a data analyst passionate about solving real-world problems, mastering fundamental analytical tools is crucial. For this reason, I conducted a detailed analysis using Jupyter Notebook on a dataset that contained sales information for various car brands. In the role of a sales professional managing multiple car brands, it is essential to perform sales analysis to identify patterns and anomalies. With my problem-solving mindset, I eagerly took on the task of analyzing the data. The process involved Exploratory Data Analysis (EDA), which allowed me to examine and visualize the dataset, gaining a deeper understanding of its key characteristics. EDA was particularly valuable as it helped summarize the data and uncover insights, serving as a foundation for more advanced analytical techniques.

### Below are the Research Questions to be answered in this analysis:

1. How many rows and columns are present in the dataset?
   
2(a) What are the data types of each column?

2(b) Are the data types for each column appropriate? If not change the data types of some columns to what they are supposed to be.

3(a) Are there any missing values in the dataset? If so, how many and in which
columns?

3(b) Fill the missing values in the year_resale_value with the average year_resale_value, then drop all other rows with missing values in the dataset.

4. Clean the name of the ‘__year_resale_value’ column by removing the leading underscore.
   
5. Do descriptive statistics (mean, median, standard deviation) of the numerical columns. What do you notice?
    
6. Are there any duplicates in the dataset?  If there are, drop them.
 
7. Which manufacturer has the highest and lowest average sales volume?
 
8. What is the distribution of car prices in the dataset?
   
9. Plot a correlation matrix to see if different numerical variables in the dataset correlate with each other.
  
10. Plot the relationship between price and latest launch year.
 
11. Group cars by manufacturers and analyze their average price and fuel efficiency.
  
12. Can you identify and visualize the most popular car brands?
    
13. Which car model has the highest resale value compared to its initial price?
    
14. Find the top 3 fuel-efficient cars with an engine size above 2.5 liters.
    
15. Which Lexus model has the highest horsepower?

#### Data Source: Practicum


 ### Data Understanding
The dataset has 156 car models, giving an insight that the sales personnel know his way around different cars and their manufacturers.  The dataset has different data types but the major is float because the numeric variables are much in the dataset.

## Methodology

#### Data Preprocessing: 

- Using python programming language for analysis, the first step is to import various python libraries to be used for the analysis and then, import the dataset to be analyzed.
- For the integrity of the analysis, the data types were checked and changed where applicable using (.info ()) as the command.
- To avoid error in analysis, duplicates were checked using (. duplicated (). Sum ()).
- Missing values were replaced using the average value of the columns involved.

 ![image](https://github.com/user-attachments/assets/c48e1099-28ba-4cfe-a92b-79a00ee2dbcd)

## Exploratory Data Analysis
1.	 In terms of average sales volume, which manufacturer has the highest and lowest? 
By combining the Manufacturers according to their mean Sales in thousands and then arranging them in either ascending or descending order, we may determine which is highest and lowest. idmax() and idxmin() can also be used in place of sorting to determine the highest and lowest average sales volume, respectively. 
2.	Distribution of car prices in the dataset

 ![image](https://github.com/user-attachments/assets/9bf78df2-bdc8-40d9-8b48-36fedd840001)

Here, we group and plot the Manufacturer with the sum of the Price in thousand.
3.	Correlation matrix of numerical variables in the dataset
 
 ![image](https://github.com/user-attachments/assets/6945e941-9d10-4c04-9d38-f359c17256cf)

4.	Which is the most popular car brands?

 ![image](https://github.com/user-attachments/assets/3a54b2d4-7209-4430-a2d2-d16d7b262846)

By grouping the Manufacturer together with the maximum sales in thousand, we can see that Ford, particularly the F-Series model is the most popular car.
5.	What is the top 3 fuel-efficient cars with an engine size above 2.5 litre

 ![image](https://github.com/user-attachments/assets/bd982f5d-b917-4011-899d-4ff1e90a26f3)

From the image above, the Chevrolet Impala, Chevrolet Monte Carlo and Mercedes CLK Coupe model are the 3 top fuel efficiency cars with an engine size above 2.5 litres.

## CONCLUSION/RECOMMENDATION
Based on our analysis, we’ve been able to provide valuable and data driven answers to our business questions. Recommendation is that a perfect analysis can be done on a wide/large dataset. Visualizations can then be done on PowerBI and other advanced analytics tools.

