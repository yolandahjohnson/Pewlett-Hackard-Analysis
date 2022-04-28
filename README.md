# Pewlett-Hackard-Analysis

## Overview of the Analysis:

The purpose of this analysis is to determine the following:

- The number of retiring employees per title
- Identify employees who are eligible to participate in a mentorship program

## Results

### Retiring Employees by Title

To obtain the number of retiring employees by title, I created table Retirement Titles. This table returned 133,776 employees by titles. Due to promotions or reassignments, individual employees have held more than one title, therefor the results contained multiple titles for individual employees.  
![retirement_by_title_duplicates](https://user-images.githubusercontent.com/100816778/165651189-ee56cd90-2563-45c4-9274-02a18ab78ae2.png)

Using the DISTINCT ON function, duplicate employees were removed from the table to indicate only the most recent title held. This table ,Unique Titles, returned 90,398 employees by title.

![retirement_by_title_no_duplicates](https://user-images.githubusercontent.com/100816778/165652953-c03ec0fe-22f0-4b64-8906-f1549955f3b8.png)

In order to get a count of retiring employees for each title, I created the Retiring Titles table. This table shows how many employees that will be retiring that hold a specific title. 

![retiring_per_title](https://user-images.githubusercontent.com/100816778/165653669-82bee493-672f-40d3-b05c-af1b6a3bf305.png)

### Employees Eligible for the Mentorship Program

To determine the employees that are eligible for the mentorship program, the Mentorship Eligibility table was created. This table shows all employees born between January 1, 1965 and December 31, 1965. There are a total of 1,940 eligible employees for the mentorship program.

![mentorship_eligibilty](https://user-images.githubusercontent.com/100816778/165655216-9b3d226f-973d-405c-aef0-a0ff726c85a1.png)

### Summary

## How many roles will need to be filled as the "silver tsunami" begins to make an impact?
- There are a total of 90,398 employees that are approaching retirement.
- Approximately 64% of that number are Senior Engineers and Senior Staff.
- This indicates a large number of top level employees with the most knowledge and experience will be retiring soon.

## Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
- Yes! The bulk of the 1,940 eligible employees for the mentorship program are senior level employees. They have the necessary experience to mentor the next generation.  

![number_eligible_by_title](https://user-images.githubusercontent.com/100816778/165656811-99a24bc7-1cbc-4e6f-8a2e-51740d6731ba.png)
