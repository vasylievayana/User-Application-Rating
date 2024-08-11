# User Application Rating
This project involved calculating  the rating of user applications based on various criteria using Pandas in Python. The data is processed, cleaned, and merged from two CSV files: `applications.csv` and `industries.csv`. The final output is a visualization showing the average rating of accepted applications by week and a histogram visualizing the distribution of ratings.

## Project Steps

1.	**Data Loading and Cleaning:**
   - Load data from `applications.csv` and `industries.csv` into DataFrames.
   - Removing duplicate entries based on `applicant_id`.
   - Filling missing values in the `External Rating` field with 0.
   - Filling missing values in the `Education level` field with "Середня" .

2. **Merging Data:**
   - Merging the applications data with the industry ratings data.

3. **Rating Calculation:**
   - Calculating the application rating based on six criteria.

4. **Filtering:**
   - Selection of applications with a rating greater than zero.

5. **Visualization:**
   - Grouping the data by application week and visualize the average rating of accepted applications per week. 
   - Creating a histogram to illustrate the distribution of application ratings.
