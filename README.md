# Pewlett-Hackare-Analysis
Module 7: Employee Database with SQL

## Overview of the analysis
In this module we're using SQL to help Bobby perform analysis on the employees of the company Pewlett Hackard.
We created an ERD based off of existing csv files, then performed analysis on the data using SQL within pgAdmin 4.
We filtered and combined the data tables to find employees likely to be retiring soon and employees eligible for a potential mentorship program.


## Results

* There are 90398 current employees that meet the retirement qualification of being born between 1952 and 1955.

![Any_title](https://raw.githubusercontent.com/mdwilliams11/Pewlett-Hackare-Analysis/main/total_retirement_count.png)


* There are 29414 Senior Engineers, 28254 Senior Staff, 4502 Technique Leaders, and 2 managers expected to retire.

![Any_title](https://raw.githubusercontent.com/mdwilliams11/Pewlett-Hackare-Analysis/main/retiring_titles.png)


* There are 1549 current employees eligible for the potential mentorship program.

* The data format denoting all current employees as having a to_date of 9999-01-01 will have to be updated sometime in the next 8000 years.


## Summary

*How many roles will need to be filled as the "silver tsunami" begins to make an impact?*

There are expected to be 90398 employees retiring, with an expected 1549 current employees eligible for a potential mentorship program.
It is doubtful that the 1549 current employees can take on the management responsibilities of the 90398 retirees. 
If we expanded the eligibility of the mentorship program from employees born in 1965 to employees born between 1963 and 1967, then the eligibility number jumps up to 38401.
Pewlett Hackard will have to expand the mentorship eligibility or bring on a significant amount of management from outside the company in order to replace the retiring employees.

![Any_title](https://raw.githubusercontent.com/mdwilliams11/Pewlett-Hackare-Analysis/main/expanded_mentorship.png)


*Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?*

There should be enough current employees out of the 90398 expected to retire to mentor the 1549 employees eligible for the mentorship program.
Of the retiring employees, 29414 are Senior Engineers, 28254 are Senior Staff, 4502 are Technique Leaders, and 2 are managers.

![Any_title](https://raw.githubusercontent.com/mdwilliams11/Pewlett-Hackare-Analysis/main/retiring_titles.png)