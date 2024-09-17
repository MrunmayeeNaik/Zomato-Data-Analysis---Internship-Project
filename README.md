# Zomato-Data-Analysis-Project
The Zomato Data Analysis project invovles analyzing data to get useful insights into restaurant operations, customer preferences and market trends. It invovles data preprocessing, exploratory data analysis to derive meaningful insights.
## Dataset
The dataset consist of 7 columns that has restaurant-related information namely : name of restaurants , ratings , votes , listed type , online order , table booking and cost for two.
It helps to understand customer preferences and restaurant performance.

## Tools and Libraries used
* Google Colab
* Python Libraries :
* Numpy and Pandas - For Data Manipulation.
* Matplotlib and Seaborn - For Data Visualization.
## Data Cleaning & Preprocessing 
* The rate column that shows rating of a restaurant, was intially shown as 4.5/5 so it cleaned using a custom function to extract the numerical rating from the text as 4.5.
* Ensured that there are no null values in the dataset.

## Analysis Questions.
1. What type of restaurant do majority of customer orders from ?
2. How many votes has each type of restaurant received from customers?
3. What are ratings that majority of restaurant have received ?
4. Zomato has observed most couples order most of their food online? What is their average spending on each order ?
5. Which mode(online or offline) has received maximum rating ?
6. Which type of restaurant received more offline orders, so that Zomato can provide customer with some good offers ?

## Visualizations 
* Countplot showing types of restaurant customer prefer.
* Line plot visualizing the total votes received for each restaurant type.
* Histogram representing distribution of ratings.
* Heatmap to observe online vs offline orders for each type of restaurant.

## Key Insights
* Dining is most customer's first preference and has received maximum votes also.
* The majority of ratings is observed to be between 3.5 to 4.
* Online orders have received maximum ratings then offline.
* Dining restaurants observe more offline orders.

