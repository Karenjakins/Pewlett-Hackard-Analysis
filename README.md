# Pewlett Hackard Analysis

## **Overview of Project**

The purpose of this analysis is to conduct a Database analysis for Pewlett Hackard with detailed information on the number of future retirees from all departments currently working at the company to be able to prepare a plant to hire new staff and also to prepare a mentorship initiative. 

The critetion was based on the birth dates ranging from 1952 to 1955 and hired dates from 1985 to 1988.


## Results

- Below is the ERD (Entity Relationship Diagram) used to visualize the relationship between the data sources and the structure of the company's employee plan to facilitate the analysis. 

	![alt text](https://github.com/Karenjakins/Pewlett-Hackard-Analysis/blob/main/EmployeeDB.png "Employee DB")

### Future Job Openings 

- After conducting the analysis it was found that there is currently a large number of employees of retirment age holding senior titles (57,668/90,398 = 64%) with around **64%** of the staff to retire. Please reference the Unique Titles table below. 
	
	![alt text](https://github.com/Karenjakins/Pewlett-Hackard-Analysis/blob/main/Queries/Unique%20Titles.png "Unique Titles")


### Mentorship Candidates

- Below is the list of candidates that can qualify to become members of the mentorship program, they can be referenced as "senior" employess amongst the general staff. 

	![alt text](https://github.com/Karenjakins/Pewlett-Hackard-Analysis/blob/main/Queries/Mentorship%20Eligibility.png "Mentorship Candidates")
	

## Summary




## Resources

**Data Sources:** departments.csv, dept_emp.csv, dept_manager.csv, employees.csv, salaries.csv, titles.csv

**Software:** SQL, PostgreSQL, pgAdmin