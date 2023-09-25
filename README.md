# Culinary Data Explorer: Zomato Edition
## Exploration and Analytical Study using SQL (SQL SERVER)

Zomato is a well-known Indian multinational restaurant aggregator and food delivery establishment. The analysis of the Zomato dataset aims to render an insightful overview of the ongoing activities and operations within the company’s business. The dataset encompasses over 9000 rows, featuring columns including Restaurant_id, Restaurant_name, City, Location, Cuisines, amongst others.

### Data Exploration Process:

Throughout the data exploration stage using SQL, the following tasks were executed:

1. **Table Inspection:**
   - Reviewed the table structure, including column names, data types, and constraints.
   - Investigated the presence of duplicate values in the [RestaurantId] column.
   
2. **Data Cleaning:**
   - Eliminated unnecessary columns from the table.
   - Identified and amended misspelled city names.

3. **Data Transformation and Enhancement:**
   - Executed the merger of two distinct tables, subsequently appending a new column, [Country_Name], utilizing [CountryCode] column as the primary key.
   - Deployed window functions for rolling/moving count to enumerate the number of restaurants.

4. **Statistical Analysis:**
   - Performed descriptive statistical analysis on votes, rating, and currency columns to determine minimum, maximum, and average values.
   - Formulated a new category column for rating.

### Data Analysis Insights:

Upon concluding the data exploration stage, the analytical phase commenced, revealing several insights pertinent to the dataset. For instance:

1. **Demographic Analysis:**
   - A substantial 90.67% of the dataset pertains to restaurants located in India, followed by the USA, constituting 4.45%.
   
2. **Online Delivery Insights:**
   - Among 15 countries represented, only India and the UAE provide online delivery options, with 28.01% and 46.67% of restaurants offering this service, respectively.
   
3. **Geographical Insights:**
   - Given the dataset’s significant emphasis on India, the focus was directed towards acquiring insights concerning Indian Restaurants.
   - Connaught Place in New Delhi emerged with the highest number of listed restaurants (122), succeeded by Rajouri Garden (99) and Shahdara (87).

4. **Cuisine Preferences:**
   - North Indian Food is the predominant cuisine in Connaught Place.
   
5. **Service Analysis:**
   - Of the 122 restaurants in Connaught Place, only 54 offer table booking facilities.
   - The average rating for restaurants providing table booking is 3.9/5, while those without this feature have an average rating of 3.7/5.

6. **Economic Insights:**
   - The optimal moderately priced restaurant, with an average cost for two being less than 1000, a rating exceeding 4, over four votes, and offering both table booking and online delivery options with Indian cuisines, is 'India Restaurant' located in Kolkata, India (RestaurantID - 20747).

### Conclusion:
The insights derived from this dataset not only facilitate a comprehensive understanding of Zomato’s operational dynamics but also furnish pivotal information beneficial to stakeholders for making informed decisions and strategic advancements in the restaurant and food delivery sector.
