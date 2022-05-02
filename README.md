### The Cutlery Group_Project_1

## Background

The Cutlery Group set forth to review data regarding restaurants. The Cutlery Group conducted analysis to determine whether  ratings supported food quality.  Also does the price point matter in determining what’s considered e a great experience? Are there cities that review more than others? 

The collaborative effort was to gather varuius restaruant information in the most populated cities in the United States. From this data, further analysis including ratings, pricing and reviews.  From this, there could be multiple coorelations that could be reviewed.


## Work

Key tasks are the following:

* Prepare the data.

* Generate summary statistics.

* Create visuals including bar charts.

* Create a scatter plot.

* Calculate correlation and regression. 

* Submit final analysis. 

## Tools/Modules:
A Excel

B Python

C Pandas

D Matplotlib

E pprint

F Numpy

G Powerpoint

H APIs


## Analysis Questions 

Does pricing influence ratings?

Does pricing influence the number of reviews?

Does population influence rating?

Does population affect the number of reviews?

## Data Preparation

    1. Run dependency and data imports, and then merge the DataFrames into a single DataFrame.
        - Censuscsv
        - Google places API 
    2. Display the number of unique cities in the data.
    3. Display the data associated with restaurants and ratings, create a new DataFrame then clean     
       DataFrame for the remaining step.
    4. Display the updated number of unique cities.

## Summary Statistics Generation

Create summary statistics DataFrames:

     1. Utilzation of the "groupby" method to generate the city and ratings.
     
     2. Combine objects into a single summary statistics DataFrame.
    

![image](https://user-images.githubusercontent.com/99145651/166159795-04cd8b48-d4a7-418b-bc4a-1ef92e7dad3e.png)

    
## Bar Charts Creation

     1. Generate bar plots showing the total number of ratings. 
                * Create bar plot by using Pandas's `DataFrame.plot()` method.
    
  
 ![image](https://user-images.githubusercontent.com/99145651/166159829-8b12c345-8e75-4ece-8800-d916f19f8638.png)

               
## Scatter Plot Creation 
      
      1. Generate a scatter plot of ratings versus price.
      
      
  ![image](https://user-images.githubusercontent.com/99145651/166159878-01d3ef12-b05f-4edc-9723-5f0f17e57da6.png)


## Correlation and Regression Calculation 

      1. Create correlation coefficient and linear regression models. 
      2. Plot the linear regression model on top of the previous scatter plot.
      
   ![image](https://user-images.githubusercontent.com/100813963/166336556-acdfbd52-232f-4386-bb87-8946e635a0aa.png)
   ![image](https://user-images.githubusercontent.com/100813963/166336664-685fa2ad-90ea-4f39-b8a7-888fb557cd82.png)

   ![image](https://user-images.githubusercontent.com/100813963/166336192-24bd0a03-012c-49e7-900b-7e404507d62e.png)
   ![image](https://user-images.githubusercontent.com/100813963/166336237-669fa75b-4b84-4745-8495-f93a61872ac1.png)

### Summary

Major Findings from Project 1

The Cutlery Group conducted analysis to determine whether different variables impacted restaurant reviews. This analysis utilized Google API for restaurant data and US city population data. What we set out to find in Project 1 was to answer these four questions:
1.	Does pricing influence ratings?
2.	Does pricing influence the number of reviews?
3.	Does population influence rating?
4.	Does population affect the number of reviews?

What we found from the data collected was that we have weak correlations between:
1.	Price level and customer rating, the R-Square Value was: 0.28, this would make sense because there is a known thought that as you spend more money, you should be receiving higher quality service.
2.	Price level and the number of ratings, the R-Square Value was: -0.21, this had a negative R-value which showed that as the price level went up the restaurant received less reviews. Which made sense as price level increases its harder for your average families to go out and spend more money on food. The data showed that your average individual going out to eat stayed between the 2-3 price level range
3.	Population size and rating, the R-Square Value was: -0.21, this had a negative correlation as well. As the population got larger the average rating started to decrease. This could be due to the larger diversity of people, and maybe easier availability to more of the same food which would be a competition factor.

We found no correlations between:

4.	Population size and people submitting reviews, the R-Square Value was: 0.11, this had the lowest R-Square value. This could be due how the question was worded or from the data sample we had. We figured as a population increased, we would see more reviews, but this was not how it turned out. Maybe some ways to approach this question better next time would be to change the location of the center of latitude and longitude to a more active spot in the city, or to increase the radius so that more restaurants are include in the data.
This has been our conclusion for project 1.


![image](https://user-images.githubusercontent.com/99145651/166160155-4effa2c4-672b-464f-80ab-6e123afaf80d.png)

