# Pewlett Hackard Analysis

## Overview of the Project
<p align="justify">The purpose of this project was to analyze a large dataset of a company named Pewlett Hackard. The company is interested in employees that will be retiring soon and it is also concerned about which positions will need to be filled in the future. This analysis will give Pewlett Hackard the necessary data in order to make decisions and offer a retirement package for the employees that will be retiring.  
In addition, the manager that is supervising the analysis wants to create a mentorship program for some of the company’s employees that meet certain criteria.</p>

## Results
<p align="justify">There were 4 tables created in this analysis:</p>
1.	A retirements title table which shows the titles of the employees born between the years 1952 and 1955. These years were chosen because the manager considered that the employees born between those dates are the one that could be retiring soon.

<img width="393" alt="1" src="https://user-images.githubusercontent.com/111388644/197619825-97b93de3-3d7f-4b90-8594-3cfeb4a5d399.png">

<img width="497" alt="1 1" src="https://user-images.githubusercontent.com/111388644/197619884-d8a8b602-71d3-48b1-ae25-932c625d6354.png">

2.	A Unique title table that displays the same information of the retirements title table without the employees that are repeated. For this result the *DISTINCT ON* function was used. Also, a statement was added to exclude the employees that have already left the company. 

<img width="349" alt="2" src="https://user-images.githubusercontent.com/111388644/197620015-857ab618-02be-43c4-8837-12e11c856e9b.png">

<img width="373" alt="2 1" src="https://user-images.githubusercontent.com/111388644/197620043-614b0eb5-61f5-41a7-8c6f-32da30d58cae.png">

3.	A retiring table which shows the number of employees that are about to retire, including their most recent job title. For this table the *ORDER BY* function had to be used with the count column.

<img width="254" alt="3" src="https://user-images.githubusercontent.com/111388644/197620096-ea56e2b8-5d9c-4be1-af38-0f8ddc7f8064.png">

<img width="189" alt="3 1" src="https://user-images.githubusercontent.com/111388644/197620114-473f202a-6f8d-4158-bd59-bd13043c848e.png">

4.	Finally, a table named Mentorship Eligibility was created. In this table it is displayed the employees that are still employed in the company and that were born in the year 1965. The employees that meet these criteria are the ones that are eligible for the mentorship program. In this table the *DISTINCT ON* function was used again. 

<img width="363" alt="4" src="https://user-images.githubusercontent.com/111388644/197620165-8c9fcd67-ed42-48be-a531-812ff8831067.png">

<img width="549" alt="4 1" src="https://user-images.githubusercontent.com/111388644/197620219-5ad8c5c5-8bb8-44a5-bc88-08a3a44333f2.png">

## Summary
-	How many roles will need to be filled as the “silver tsunami” begins to make an impact?

<p align="justify">There are 7 roles that will need to be filled. The number of employees that will retire in each roles are: Senior Engineer with 25916, Senior Staff with 24926, Engineer with 9285, Staff with 7636, Technique Leader has 3603, Assistant Engineer with 1090, and Manager with 2 employees about to retire.</p> 

<img width="189" alt="3 1" src="https://user-images.githubusercontent.com/111388644/197621372-a78061fb-23c0-44c3-a329-9fd59bd29598.png">

-	Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

<p align="justify">There are enough qualified retirement-ready employees to mentor the new generation of workers in the company. There are 1549 employees ready to retire that meet the criteria for the mentorship program.</p> 



<p align="justify">Another to queries that could help to have more depth in the analysis could be:</p>

-	How much are the employees that are ready to retire getting paid?

-	Which gender are these employees?

<p align="justify">These questions could be answered by creating a new table joining the employees, titles, and the salaries tables.</p>  

<img width="375" alt="5" src="https://user-images.githubusercontent.com/111388644/197620336-188c63fe-f1b8-416f-8fa6-fba81d1f8b9e.png">

<p align="justify">The resulting table is the one shown below.</p>

<img width="650" alt="5 1" src="https://user-images.githubusercontent.com/111388644/197620398-e468c562-8acc-4dd2-a1f3-fd4bd383aac8.png">

<p align="justify">This could help to get an idea of how much the new employees could get paid according to their experience, as well as to give an idea of the proportion of men and women that are leaving. The gender could also be compared to the salary.</p>
