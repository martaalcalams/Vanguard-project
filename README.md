Vanguards Project - README

Overview:

In this project we started with 3 main datasets.
Import all the necessary libraries.
Import all the datasets.

Create a dataframe with Dataset 1.
Clean and organize the dataframe.
Convert all columns to integers.
Define numerical and categorical columns.
Confirm there are no numerical columns with categorical potential.
Define primary columns (80% their profit) and calculate their percentage in proportion to the whole clients.
Create a csv for this new database (primary columns) to import it in tableau.
Define primary top columns (95% their profit) and calculate their percentage in proportion to the whole clients.
Comparing average ages and tenures from all clients and primary clients.
Analyze primary clients dataset:
Categorize age as: "Young", "Middle-age", "Old".
Categorize tenure year as: "New", "Mid-term", "Long-standing".
Plot a pie chart showing the age and tenure distribution.
Count number of clients grouped by gender and age category.
Plot 3 different pie charts for age distribution.
Count for logons based on gender and age.
Count of calls based on gender and age.
Categorize and plot a bar chart for client tenure distribution.
Categorize and plot a bar chart for client balance distribution.
Compute a table for a better understandingof client behaviour.

Import and create two dataframes (from final_web_data 1&2).
Create a new dataframe by concatenating these two.
Fill all na values from last dataset (final_experiment) with the mode.
Merge this last dataframe with the last dataset (final_experiment).
Calculating performance metrics from this dataframe:
Calculation of completion rate for both variation groups (Control & Test).
Calculation of time spent on each step process for both variation groups and ploting a bar chart for better visualization and understanding. 
Calculation and pie chart plot for the error rate of both variation groups.
Comparison and explanation between the two groups in completion rate.
Testing 3 hypothesis:
Completion rate, with its defined H0 and H1.
Completion rate with a cost-effectiveness threshold of +0,05%, with its defined H0 and H1.
Hypothesis testing between clients average age and step process, with its defined H0 and H1.
Checking if data is normally distributed for the full dataframe of client_age:
checking, transforming to normal distribution, re-assessing after transforming by plotting and statistical testing.

