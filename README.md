# Exploratory Data Analysis (EDA) on Zomato Dataset

This repository contains an **Exploratory Data Analysis (EDA)** of the **Zomato Dataset**. The goal of this project is to analyze and visualize the data to uncover insights about restaurants, their locations, ratings, cuisines, and other attributes.

---

## Dataset Overview

The Zomato dataset contains information about restaurants listed on Zomato, including:

- **Restaurant Name**
- **Location**
- **Cuisines**
- **Average Cost for Two**
- **Average Rating**
- **Votes**
- **Online Order Availability**
- **Table Booking Availability**
- **Restaurant Type**
- **Listed In (City and Type)**

---

## Objectives

1. **Understand the Dataset:**
   - Explore the structure and features of the dataset.
   - Identify missing values and clean the data.

2. **Analyze Key Metrics:**
   - Distribution of restaurants by location, cuisine, and type.
   - Average ratings and cost for two people.
   - Popularity based on votes and online order/table booking availability.

3. **Visualize Insights:**
   - Create visualizations to understand trends and patterns.
   - Identify the most popular restaurant chains, cuisines, and locations.

4. **Answer Key Questions:**
   - What are the most popular restaurant chains in Bengaluru?
   - Which locations have the highest-rated restaurants?
   - What is the distribution of restaurant types and cuisines?

---

## Steps Performed

1. **Data Loading and Inspection:**
   - Load the dataset and inspect its structure.
   - Check for missing values and clean the data.

2. **Data Cleaning:**
   - Handle missing values in columns like `rate`, `approx_cost(for two people)`, and `location`.
   - Convert categorical data into numerical format for analysis.

3. **Univariate Analysis:**
   - Analyze individual columns like `rate`, `votes`, `online_order`, and `book_table`.

4. **Bivariate Analysis:**
   - Explore relationships between columns like `rate` and `approx_cost(for two people)`.
   - Compare `online_order` and `book_table` availability with ratings.

5. **Multivariate Analysis:**
   - Analyze the impact of multiple factors (e.g., location, cuisine, and cost) on restaurant ratings.

6. **Visualizations:**
   - Create bar plots, pie charts, box plots, and treemaps to visualize insights.

7. **Key Insights:**
   - Identify the most famous restaurant chains in Bengaluru.
   - Determine the best locations based on ratings, number of restaurants, and other factors.

---

## Tools and Libraries Used

- **Python**
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib** and **Seaborn**: For static visualizations.
- **Plotly**: For interactive visualizations.
- **Scikit-learn**: For data preprocessing (e.g., normalization).

---

## Key Findings

1. **Most Popular Restaurant Chains:**
   - Chains like **Cafe Coffee Day**, **Domino's**, and **Bangalore Biryani House** have the most outlets in Bengaluru.
   - Chains with the highest ratings include **Fine Dining** and **Casual Dining** restaurants.

2. **Best Locations:**
   - Locations like **Koramangala**, **Indiranagar**, and **MG Road** have the highest-rated restaurants.
   - These locations also have a high concentration of restaurants offering online orders and table booking.

3. **Cuisine Analysis:**
   - **North Indian**, **Chinese**, and **South Indian** cuisines are the most popular.
   - **Italian** and **Continental** cuisines have higher average ratings.

4. **Online Order and Table Booking:**
   - Restaurants offering online orders tend to have higher ratings.
   - Table booking availability is more common in high-rated restaurants.

---

## Future Work
- Perform sentiment analysis on customer reviews.
- Build a recommendation system for restaurants based on user preferences.
- Analyze trends over time (if time-series data is available).
 
## Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.

Happy Analyzing!!





