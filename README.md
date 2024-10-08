# PySchool City District Data Analysis

 ## Watch the Demo!

<kbd> [![Watch the video](https://github.com/thaychansy/pandas-challenge/assets/161902555/635ea621-a2de-4e09-b6f0-d3227ab4ad49)](https://youtu.be/hlydL19kR4U) </kbd>


## Link to the Juypter Notebook Report

<kbd> [<img width="900" alt="image" src="https://github.com/thaychansy/pandas-challenge/assets/161902555/dee84eea-6199-4ce6-a7ee-e446790cbc61">](https://github.com/thaychansy/pandas-challenge/blob/main/PyCitySchools/PyCitySchools.ipynb) </kbd>






# Instructions
You are the new Chief Data Scientist for your city's school district. In this capacity, you'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities. As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your task is to aggregate the data to showcase obvious trends in school performance using Pandas Dataframes.




# District Summary
Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame.

Include the following:

Total number of unique schools

Total students

Total budget

Average math score

Average reading score

% passing math (the percentage of students who passed math)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed math AND reading)

# School Summary
Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school.

Include the following:

School name

School type

Total students

Total school budget

Per student budget

Average math score

Average reading score

% passing math (the percentage of students who passed math)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed math AND reading)

Highest-Performing Schools (by % Overall Passing)
Sort the schools by ``% Overall Passing`` in descending order and display the top 5 rows.

Save the results in a DataFrame called "top_schools".

Lowest-Performing Schools (by % Overall Passing)
Sort the schools by ``% Overall Passing`` in ascending order and display the top 5 rows.

Save the results in a DataFrame called "bottom_schools".

Math Scores by Grade
Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Reading Scores by Grade
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Scores by School Spending
Create a table that breaks down school performance based on average spending ranges (per student).

Use the code provided below to create four bins with reasonable cutoff values to group school spending.

<kbd> <img width="581" alt="image" src="https://github.com/thaychansy/pandas-challenge/assets/161902555/f1e3e902-c61a-430b-833e-2c3d04aed153"> </kbd>

Use ``pd.cut`` to categorize spending based on the bins.

Use the following code to then calculate mean scores per spending range.

<kbd> <img width="580" alt="image" src="https://github.com/thaychansy/pandas-challenge/assets/161902555/d9d5a72e-22e0-4d62-9341-deb31dfed36f"> </kbd>

Use the scores above to create a DataFrame called ``spending_summary``.

Include the following metrics in the table:

Average math score

Average reading score

% passing math (the percentage of students who passed math)

% passing reading (the percentage of students who passed reading)

% overall passing (the percentage of students who passed math AND reading)

Scores by School Size
Use the following code to bin the ``per_school_summary``.

<kbd> <img width="576" alt="image" src="https://github.com/thaychansy/pandas-challenge/assets/161902555/ec0cead0-0d0f-4137-ba74-6d81220e465f"> </kbd>

Use `pd.cut` on the "Total Students" column of the per_school_summary DataFrame.

Create a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).

Scores by School Type
Use the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.

This new DataFrame should show school performance based on the "School Type".

# Contact
Thay Chansy - [@thaychansy](https://twitter.com/thaychansy) - or thay.chansy@gmail.com

Please visit my Portfolio Page: [thaychansy.github.io](https://thaychansy.github.io/)


# Acknowledgements
Here's a list of resources we found helpful and would like to give credit to. 

  
* [Chat GPT] [ChatGPT](https://chatgpt.com/)
* [Google Gemini] [Gemini Generative AI](https://gemini.google.com/app)







