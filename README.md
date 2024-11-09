# Restaurant-Ratings
This is an analysis of restaurant ratings data to uncover trends in customer satisfaction. The project uses Power BI to visualize insights that can guide restaurant owners and managers in enhancing service quality and customer experience.

## Project Overview
This project provides an in-depth analysis of restaurant ratings across various categories, including cuisine, location, price range, and customer demographics, using Power BI. 
The goal is to offer insights that can help restaurants and stakeholders understand customer preferences, ratings patterns, and the influence of factorslike price, service, and atmosphere on ratings.

## Data Source
Comma Separated Values File (.csv) from **TriInspire Tech Ltd** [LinkedIn](https://ng.linkedin.com/company/tri-inspire-tech-ltd)

## Tools 
- Power BI [Download here](https://www.microsoft.com/en-us/download/details.aspx?id=58494)
  - Data Cleaning and transformation
  - For data visualization
  - Reporting.
- Github [Sign up](https://github.com/join)
  - Portfolio building.

## Data Cleaning and Transformation

### 1. Loading Data into Power Query
- **Import Data**: Load data from sources like Excel, SQL, CSV, etc., using **Get Data**.
- **Access Power Query**: Open **Transform Data** to access Power Query Editor, where cleaning and transformation will be applied.

### 2. Data Cleaning

- **Remove Duplicates**: 
  - Removed duplicates under the home tab to ensure data uniqueness.

- **Handle Missing Values**: 
  - Used replace values in the transform tab to replace nulls.
 
- **Ensure Data Type Consistency**: 
  - Assigned each column a correct data type (e.g., text, wholenumber, date). 

### 3. Data Transformation

- **Merge Queries**: 
  - Merge all five (5) tables; consumer_preferences, restaurant_cuisines, consumers, ratings and restaurants into one (Ratings) by using the merge queries option.

- **Merge Columns**: 
  - Concatenate multiple columns by creating a **Custom Column** with an expression for merging.

- **Filter Rows**: 
  - Use column filter drop-downs to apply conditions.

- **Add Custom Calculations**: 
  - Create conditional columns.

### 4. Finalizing Data for Analysis

- **Apply and Load**: After completing data cleaning and transformation, I clicked **Close & Apply** to load the processed data into Power BI for visualization and analysis.


## Visualizations and Reporting

![Restaurant a](https://github.com/user-attachments/assets/1f5a94e3-da6a-4b3b-9332-8bf937254cab)

- **Consumer Demographics**
  - Age : The average age of consumers is 30 years. 
  - Occupation and Budget: Most customers are employed, with a significant portion in the medium-budget category.
  - Drinking and Smoking Habits: Consumer preferences in drink level (casual, social) and smoking (smoking section, no smoking) are also analyzed.
  - A higher percentage of consumers prefer mexican cuisine.
  - Over 70% of consumewrs do not smoke
  - 71 consumers are from San Luis Potosi,33 are from Ciudad, 23 from Cuernavaca and 3 from Jiutepec.
  - Most consumers are single and have independent children.

![Restaurant b](https://github.com/user-attachments/assets/2bb10845-f903-4a7a-b148-9f8a9eeaf2d8)

- **Restaurant Characteristics**
  - There are 130 restaurants with 22 cuisines
  - Seafood, Japoanese, Burgers cuisines are the highest in terms of sales
  - 60 restaurants offer medium pricing, 45 offer low and 25 offer high price.
  - Mexican and bar cuisines are the most popular cuisines in restaurants.
  - Most restaurants are in Tamaulipas and do not allow smoking
  - Over 80% of restaurants are not franchise and most do not allow smoking.

 ![Restaurant c](https://github.com/user-attachments/assets/c55f7188-2967-4a64-b5e4-d0064483adaf)
 
- **Ratings Analysis**
  - American and Bakery cuisines have the highest food rating.
  - Restaurants with closed area are rated highest.
  - Breakfast and Burgers have the highest food rating by preferred cuisine.
  - Consumers with high budget  gave the highest rating.
  - Top-rated Cuisines: Mexican and Japanese cuisines tend to receive the highest ratings.
  - City-wise Performance: Ratings are analyzed across different cities, highlighting regional customer satisfaction trends.
  - Impact of Price on Ratings: Higher-priced restaurants often receive higher ratings, suggesting a correlation between price and perceived quality.
  - Alcohol and Franchise: Restaurants with full bar service generally attract higher ratings.
  - Price Range Influence: Restaurants in the medium and high price ranges tend to have better ratings overall.
  

## Conclusions
This analysis provides a clear view of factors impacting customer satisfaction in the restaurant industry. Key findings include the popularity ofcertain cuisines, the influence of price and franchise status on ratings, and city-based performance variations. These insights are valuable for restaurant stakeholders looking to enhance service quality and meet customer expectations.

## Recommendations
- **Improve Service in Low-rated Areas:** Focus on cities and regions with lower average ratings by addressing common customer pain points.
- **Invest in Popular Cuisines:** Restaurants may benefit from expanding menus to include popular cuisines such as Mexican and Japanese.
- **Consider Pricing Strategy:** Higher prices are associated with better ratings, indicating that perceived value impacts satisfaction. Restaurants could assess their price offerings to optimize customer experience.
- **Enhance Customer Experience in Non-alcoholic and Non-smoking Options:** Given customer preferences, ensuring high-quality non-alcoholicand non-smoking options could improve satisfaction for a significant segment of restaurants.
