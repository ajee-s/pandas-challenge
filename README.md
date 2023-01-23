# pandas-challenge
DS Module 4 Homework
<<<<<<< HEAD
=======
DS Module 4 Homework
>>>>>>> 01137ec85a09b537b3753a87421e638324a9ac8c

In this assignment, you’ll create and manipulate Pandas DataFrames to analyze school and standardized test data.

Background
You are the new Chief Data Scientist for your city's school district. 
In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyze the district-wide standardized test results. 
You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. 
Your task is to aggregate the data to showcase obvious trends in school performance.

* Read the two csv files to collect the data
* Merge the two datasets using School Name. This will provide a complete data set with school type, budget included with the student_complete dataset.
* Perform calculations to get the metrics for the school disctrict, create a dataframe and display the results
* Next perform calculations for school level metrics for each school, create a dataframe and display the results -> per_school_summary
* Sort the school level dataframe to show the top and bottom 5 and display the results in dataframes


Math Scores by Grade
* Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Reading Scores by Grade
* Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Scores by School Spending
* Create a table that breaks down school performance based on average spending ranges (per student).

    * Create bins for school spending categorization and group schools by spending 

    * Calculate mean scores per spending range and create dataframe to display the results


Scores by School Size

* Create a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).

Scores by School Type
* Use the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.
     *Create and display a dataframe that displays school performance based on the "School Type".


# PyCity Schools Analysis Summary

* Small sized and medium sized schools performed better than Large sized schools across all performance categories. To illustrate, Average Math Passing was at 93.55% - 93.59% for the small and medium schools. Large schools had 69.96% Math Passing rate.
* District schools are spending higher per student on an average ($643.57) compared to Charter Schools ($599.5) 
* Charter school score metrics suggest students are outperforming in all categories.
* This analysis tells us higher spending per student doesn’t automatically yield better results.
* This also requires further analysis of Charter School practices vs. District School practices to see how District schools can gain efficiency.
* Overall, schools in the spending range less than $585 per student performed better than ones spending more. In fact, with the increased spending the results seemed to go down instead of improving. 
* This requires further analysis of budget spending is currently implemented

<<<<<<< HEAD

Draws two correct conclusions or comparisons from the calculations (10 points)
=======
>>>>>>> 01137ec85a09b537b3753a87421e638324a9ac8c
