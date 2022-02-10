# Overview of the analysis
Bobby's tasks were to determine the number of retiring employees per title and identify employees who are eligible to participate in a mentorship program.
He needs to help his manager understand "Silver Tsunami" is coming as many current employees are reaching their retirement age.

# Results 

* When you look at the retirement titles table, there are a lot of employees with duplicated titles. 
  * For example, employee number 10004 Chirstian Koblick has 2 titles (Engineer and Senior Engineer). But the information for his from_date and to_date are not the same. 

![retirement_titles](retirement_titles.png)

* So Bobby had to get the table that shows the employees with unique titles.
  * Now the information is more clean with "most recent job titles"

![unique_titles](unique_titles.png)

* Then, Bobby could retrieve the number of employees by their most recent job title who are about to retire. 
  * There are more than 70,000 employees by their most recent job title who are about to retire: 72,458 

![retiring_titles](retiring_titles.png)

* Now, Bobby was able to retrieve the employees eligible for the mentorship program.

![mentorship_eligibility](mentorship_eligibility.png)

# Summary

* How many roles will need to be filled as the "silver tsunami" begins to make an impact?
* Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
