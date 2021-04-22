# Pewlett Hackard Analysis

## **Overview of Project**

The purpose of this analysis is to conduct a Database analysis for Pewlett Hackard with detailed information on the number of future retirees from all departments currently working at the company to be able to prepare a plant to hire new staff and also to prepare a mentorship initiative. 

The critetion was based on the birth dates ranging from 1952 to 1955 and hired dates from 1985 to 1988.


## Results

- Below is the ERD (Entity Relationship Diagram) used to visualize the relationship between the data sources and the structure of the company's employee plan to facilitate the analysis. 

	![alt text](https://github.com/Karenjakins/Pewlett-Hackard-Analysis/blob/main/EmployeeDB.png "Employee DB")

### District Summary 

- The overall results of the district analysis were not severely affected as can be seen on the screenshots below, the average math score before the grades were taken off the calculations was **79%** and after **78.9%**. The reading scores remained the same for both data sets at an **81.9%**.

	![alt text](https://github.com/Karenjakins/School_District_Analysis/blob/main/Resources/Before%20District%20Summary.png "Before District Summary")
	![alt text](https://github.com/Karenjakins/School_District_Analysis/blob/main/Resources/After%20District%20Summary.png "After District Summary")

### School Summary

- The overall results of the school analysis were not severely affected as can be seen on the screenshots below.

	![alt text](https://github.com/Karenjakins/School_District_Analysis/blob/main/Resources/Before%20School%20Summary.png "Before School Summary")
	![alt text](https://github.com/Karenjakins/School_District_Analysis/blob/main/Resources/AfterSchool%20Summary.png "AfterSchool Summary")

### Results after Thomas High School data was nullfied 

- After removing the data from Thomas High School its is eveident that it does not affect the overall scores for the district as the change in the data is not significant. The only area for concern was the **reading and math scores** for 9th grades as can be seen below with the value **NaN**:

	![alt text](https://github.com/Karenjakins/School_District_Analysis/blob/main/Resources/NaN%20score%20grade%209.png "NaN score grade 9")

- The same trend can be observed on the scores by **school spending, school type and school size**, the data does not provide any significant change after  having nullfied the data. 


## Summary

After comparing the data from both analysis, its hard to find major changes in the school district analysis since even after adding the NaNs to the data frame, the results were not significantly different. The passing percentages for both math and reading were not impacted by more than a grade point for the average. The values that were replaced by NaNs did not create any significant statistical difference to the results, so there could be more research conducted to see if how the results of the grade 9th student affected math and reading proficiences at Thomas High School.


## Resources

**Data Sources:** departments.csv, dept_emp.csv, dept_manager.csv, employees.csv, salaries.csv, titles.csv

**Software:** SQL, PostgreSQL, pgAdmin