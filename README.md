# Pewlett-Hackard-Analysis
## Overview:
In this analysis of the human resource deparmtnet of a finctional computer company Pewlett Hackard we examine the upcoming 'silver tsunami'. A large cohort of employees from the "Baby boom" generation is now approaching retirement age. The company has tasked us with analyzing its departments to determine exactly how many employees will be retiring from each department and we determine how many younger employees are eligible to enter an mentorship program in order to better prepare the company for the upcoming exits. We use entity relationship diagrams using QuickDBD, and pgAdmin 4 to run SQL to query the employee datafrmaes and retrieve the information discussed below.

## Results:
### A large proportion of PH employees are nearing retirement.
We pulled all the employee information from the PH database and determined how many employees from each department were born between 1952 and 1955  and their current titles. Data output looks like the table below:

![retiring_titles.png](https://github.com/andrej-arsovski/Pewlett-Hackard-Analysis/blob/main/Data/retiring_titles.png)

Tabulating totals we see that a total of 90,398 employees were born in the period between 1952 and 1955. There are a total of 300,025 employees at PH currently. The retiring cohort represents 30.1% of the workforce. This is a considerable amount and PH must plan accordingly in order for its departments to be prepared with trained employees ready to replace the outgoing ones. 

![retiring_titles_totals.png](https://github.com/andrej-arsovski/Pewlett-Hackard-Analysis/blob/main/Data/retiring_titles_totals.png)

### Senior engineers are the largest departing group.

Of the retiring cohort approximately one third are retiring Senior Engineers. Senior staff represent another third.

Looking at the departments most affected, we can see that roughly 2/3 of the future retirees come from 3 departments: Development (25,628), Production (22,199), Sales (15,699).

### A small number of employees are eligible for a mentorship 
To determine what proportion of the current workforce is eligible to be mentored by the departing cohort we pulled the current employees that were born in 1965. We found 1549 of those individulas and the ressults are stored as displayed below:

![mentorship_eligibility.png](https://github.com/andrej-arsovski/Pewlett-Hackard-Analysis/blob/main/Data/mentorship_eligibility.png)

### Senior Staff are the largest group eligible for mentorship

Examining the titles of the group eligible for mentorship we find that the largest group is Senior Staff (569), followed by Engineers (501) and then Senior Engineers (169).

![mentorship_title.png](https://github.com/andrej-arsovski/Pewlett-Hackard-Analysis/blob/main/Data/mentorship_title.png)

## Conclusions

1. 90, 398 roles will need to be filled soon as a large cohort of Boomers will be retiring.
2. There are more than enough employees to mentor the next generation of PH employees. Currently there are only 1,549 employees eligible for the mentorship program.
3. Development, Production and Sales are most affected by the retiring cohort and will be most in need of restaffing.

![departments_afected.png](https://github.com/andrej-arsovski/Pewlett-Hackard-Analysis/blob/main/Data/departments_afected.png)

4. This is a good time to address the gender disparity at PH. Currently the work force is made up of 179,973 individulas identifyng as male while only 120,051 identifies as female. As a large group of employees readies to leave the PH workforce this is a good time to address this issue. It would also be good to examine the racial make up of the workforce to see how that can be improved in the future.

![retiring_gender.png](https://github.com/andrej-arsovski/Pewlett-Hackard-Analysis/blob/main/Data/retiring_gender.png)

