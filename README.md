# Pewlett-Hackard-Analysis

## Overview

This is an analysis of Pewlett-Hackard employee data to determine the future hiring needs based on the number of retiring employees.  Retiring employees are considered current employees born between 1952 to 1955. The analysis consisted of created a list of current employees that are expected to retire based on their title.
Additionally, an analysis was done to identify employees who are eligible to participate in a mentorship program, to help with development of future hires. 

## Results

* From the current_emp table we can see that there 33,118 current employees who are eligible to retire. 
* Development (9281), Production (8174) and Sales (5860) were the top three departments with the most employees eligible to retire
![retirement by departments](https://user-images.githubusercontent.com/62673123/128450083-7be4285e-a24a-4475-91c3-750fbb3309b2.PNG)

* From the retiring_titles tables there a total of 90,398 employee titles that need to be replaced.
![retirement by position](https://user-images.githubusercontent.com/62673123/128450140-f9e1bd4e-d97c-49ac-a42a-b12b10656a37.PNG)

* There is also some issues with the data.  While we show 33K current employees who are eligible to retire, we also show that there are about 90K unique position titles based on the retiring_titles table that are eligible for retirement.  The current_emp table in addition to be sorted by date of birth also was sorted by hire date, while the retiring_titles table was not, which result in the greater number in the retiring_titles table. 

## Summary

From the current_emp table we can see that there 33,118 current employees who are eligible to retire. 
There are a total of 1549 current employees who are eligible as mentors.  If each of the approx. 33k positions is to be filled, that would mean 1 mentor for each 22 new employees in the coming years.  That does not consider the different departments and positions that will be filled and of the eligible mentors which department and position they from.
