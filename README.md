# COVID19_clinicaltrials_EDA
The objective of the project, 'COVID-19 clinical trials EDA' is to gain characteristics of COVID-19 clinical trials, such as their status, phases, study designs, and demographics.
Given dataset: COVID clinical trials.csv
Number of rows: 5783
Number of columns: 27
Removed columns with excessive missing values(Acronym, Study Documents)
A bar chart of missing data percentages was generated.
Replaced NaN values with Missing column name for the categorical values.
Replaced missing Result First posted with Unknown.
Analyzed the distribution of:
 Status of clinical trials- completed, not yet recruiting, withdrawn etc
 Gender distribution – Male, Female, All, Missing gender
 Understanding the distribution of trial phases –Phase1, phase2 etc
 Top 10 Age groups
Analyzed the relationship between two variables:
 Status vs Phase:  stacked bar charts to show counts of trials in each phase by their status.
 Status vs Age: stacked bar chart to show relationship between age groups and trial status
 Gender vs Status: stacked bar chart to show gender distribution across trial status.
Convert the Start Date and Primary Completion Date column to datetime format
Plots a line chart showing how the number of trials changed over the time.
The chart will likely show an increase in trials during mid 2020.






