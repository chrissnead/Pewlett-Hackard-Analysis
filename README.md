# Pewlett-Hackard-Analysis

## Overview
This analysis breaks down the age of employees and amount of time they've been with the company to determine the impact retirement is going to have on each department.

## Results
- The *retirement_titles* table groups all employees together who are eligibile for retirement.
![Retirement Titles](Data/retirement_titles.csv)
- As you can see from the *retirement_titles* table, there are duplicate names shown. This is because over time people have had different titles within the company. In the *unique_titles* table, we fix that by pulling only the most recent title for each employee eligible for retirement.
![Unique Titles](Data/unique_titles.csv)
- The *retiring_titles* table breaks down the total retirement number by department in order to assess where retirement will be most impacted.
![Retiring Titles](Data/retiring_titles.csv)
- The *mentorship_eligibility* filters down the employees that are able to mentor lower level employees to replace those getting ready to retire.
![Mentorship Eligibility](Data/mentorship_eligibility.csv)

## Summary
72,458 roles will need to be filled as the "silver tsunami" begins to make an impact. There are only 1,549 qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees, so major employee developments and hiring decisions are going to need to happen to combat the loss of senior talent.
