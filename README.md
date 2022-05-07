# Retirement Impact

## Overview
This analysis measures the age of employees compared to the amount of time they've been with the company to determine the impact retirement is going to have on each department. These results will be used to create a mentorship program that will help train current employees to fill the roles of those retiring and create a smooth transition for new talent to join the company.

## Results
- The [Retirement Titles](Data/retirement_titles.csv) table groups all employees together who are eligibile for retirement.
- As you can see in the *Retirement Titles* table, there are duplicate names shown. This is because over time people have had different titles within the company. In the [Unique Titles](Data/unique_titles.csv) table, we fix that by pulling only the most recent title for each employee eligible for retirement.
- The [Retiring Titles](Data/retiring_titles.csv) table breaks down the total retirement number by department in order to assess where retirement will be most impacted.
- The [Mentorship Eligibility](Data/mentorship_eligibility.csv) filters down the employees that are able to mentor lower level employees to replace those getting ready to retire.

## Summary
72,458 roles will need to be filled as the "silver tsunami" begins to make an impact. There are only 1,549 qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees, so major employee developments and hiring decisions are going to need to happen to combat the loss of senior talent.

## Resources
- Language(s): SQL
- Tools: PostgreSQL, pgAdmin
