# Social-Buzz-Data-Analysis
### This Project is part of Accenture Virtual Internship Program
![accenture logo](https://github.com/Ameya1393/Social-Buzz-Data-Analysis/assets/84855509/44a61272-ea98-4a03-8b1b-7432d3db3e5b)

## Client background:
#### Social Buzz was founded by two former engineers from a large social media conglomerate, one from London and the other from San Francisco. They left in 2008 and both met in San Francisco to start their business. They started Social Buzz because they saw an opportunity to build on the foundation that their previous company started by creating a new platform where content took center stage. Social Buzz emphasizes content by keeping all users anonymous, only tracking user reactions on every piece of content. There are over 100 ways that users can react to content, spanning beyond the traditional reactions of likes, dislikes, and comments. This ensures that trending content, as opposed to individual users, is at the forefront of user feeds. 

## Scenario: Our team of dedicated professionals at Accenture has been tasked with analyzing and visualizing data for Social Buzz. This documentation serves as a comprehensive resource to understand the project's objectives, methodologies, and outcomes.

# AIM: - An analysis of their content categories that highlights the top 5 categories with the largest aggregate popularity.

## Tools Used: Microsoft Excel & SQL

## Step 1: Data Modelling

### Data Model - [Data Model Link](https://drive.google.com/drive/folders/17Z_Ypx7xBC9h_RBYq64LiKekYYcjrX4T)

### -> After a thorough review of the data model, it has become evident that merging three key tables—Reaction, Content, and Reaction Types—is essential to categorize the top 5 most popular categories effectively. 

## Step 2: Data Cleaning
### Tasks Performed:
1. **Handling Null Values**: The first task was to identify and remove any Null (missing) values within the Excel sheet. Null values can lead to erroneous analysis results, so it was imperative to eliminate them to maintain data integrity.
2.  **Removing Unnecessary Tables**: To streamline our dataset and focus on relevant information, I removed extraneous tables and data that were not pertinent to our analysis objectives. This step helped declutter the dataset and improve overall clarity.
3.  **Addressing Formatting Inconsistencies**: I addressed any uneven formatting issues within the data. This included standardizing date formats, text capitalization, and ensuring uniform units of measurement where applicable. Consistent formatting is essential for accurate analysis.
4.  **Final Data Validation**: Before proceeding to the analysis phase, I conducted a final comprehensive check on the cleaned data to ensure that it was in an optimal state for analysis. This validation step involved confirming data consistency, accuracy, and completeness.

Find the cleaned Datasets attached Below-
[Cleaned Datasets](https://drive.google.com/drive/folders/1JOXaWKpmd8M4cUwrgAOjvHmIMHulMSwI)

## Step 3 : Creating the Final Merged Dataset

In this phase, we proceeded to create a comprehensive and integrated dataset by merging the three primary tables: Reaction, Content, and Reaction Types. This merging process enables us to consolidate relevant information from these tables into one cohesive dataset for our analysis.

To achieve this, we followed a systematic approach:

1. We utilized the Reaction table as the base table, as it contains core data for our analysis.
2. Next, we employed the "VLOOKUP" formula to join and incorporate pertinent columns from the Content dataset. This step allowed us to enrich our dataset with additional content-related information.
3. Following that, we extended our dataset by incorporating relevant data from the Reaction Types dataset, again utilizing the "VLOOKUP" formula. This enhanced our dataset with valuable insights into various reaction types.

## Step 4: Determining the Top 5 Performing Categories

Our primary goal in this phase was to identify the top-performing content categories. To accomplish this, we aggregated data from the merged dataset and calculated the total scores for each category. This was achieved using the "SUMIF" formula.

The outcome of this phase is a single, well-structured spreadsheet that encompasses:

1. A thoroughly cleaned and integrated dataset, free from inconsistencies or missing values.
2. A clear identification of the top 5 performing content categories based on their total scores.

#### This consolidated dataset and the insights into the top-performing categories will serve as the foundation for our subsequent data analysis and visualization efforts, allowing us to make informed decisions and provide valuable recommendations to our client, Social Buzz.

Find the Resultant Excel sheet here - [Result Sheet](https://drive.google.com/drive/folders/1lxItQmjd8clcIQ-qq1HTGbJ13ncHKLze)

## Step 5: Data Visualization

Following the identification of the top 5 performing content categories, the next crucial step in our data analysis process was to provide stakeholders with a clear and visually appealing representation of this information. We accomplished this by creating both bar graphs and pie charts to present the data in an easily digestible format.

#### Find the Visualizations attached Below - 

![Bar graph](https://github.com/Ameya1393/Social-Buzz-Data-Analysis/assets/84855509/0816eda9-54ee-4758-b1d3-23ef46e06607)

![Pie chart](https://github.com/Ameya1393/Social-Buzz-Data-Analysis/assets/84855509/4fbea212-de1c-4246-8c0f-1d9e7dca2f51)

## Conclusion -
### 1. Animals and science are the two most popular categories of content, showing that people enjoy real-life and factual content the most.
### 2. Food is a common theme in the top 5 categories with healthy eating ranking the highest. Social Buzz can use this insight to create a campaign and work with healthy eating brands to boost user engagement.


