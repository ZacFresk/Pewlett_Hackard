# Objective

Bobbys manager has given you and him two more assignments after proving his SQL chops: determine the number of retiring employees per title and identify employees who are eligible to participate in a mentorship program. Then, you will create a report that summarizes your analysis and that will help prepare Bobby’s manager for the “silver tsunami” as many current employees reach retirement age.

Out goal is to determine how many employees are near retirement age and are trying to avoid a multitude of resignations without backfills prior to these individuals retiring. We have been provided six different csv files that were provided as data and merged, created, consolidated and imported data into other csv files to present digestable information to management so they can work on trying to backfill needed positions prior to current employees retirement.

# Results

- Retiring Employees filtered by Title was put together by showing all employees born between 1/1/1952 and 12/31/1955 with their current titles. This was to target the candidates who were more likely for retirement. Code:

![Deliverable 1](https://user-images.githubusercontent.com/107363203/204174869-aaf459fd-e353-4751-ad98-848ace241d7c.png)

This code gave us retirement_titles.csv - This game first name, last name, title, emp_no, and birth date.

- We were able to refine the potential retirement candidates by using the following code: 

![Retirement Titles](https://user-images.githubusercontent.com/107363203/204174965-bd5e8efb-3b38-4024-bdb9-79e3beafa221.png)

We then removed duplicates if someone had multiple titles during their tenure or anyone who was promoted. By using to date 1/1/9999 it gives us their most up to date title.

- Lastly, we summarized this data for viewing:  

![Filtered Data](https://user-images.githubusercontent.com/107363203/204174919-e1a74d9c-98c1-48f5-a889-85790dad4784.png)

![Unique Title Counts](https://user-images.githubusercontent.com/107363203/204175077-5ed5457c-e746-4cc3-9c92-c772444d7484.png)

Based on these summarized data points we can determine the following:

- There were almost 72,000 staff close to retirement  in the unique_titles report.
- For these two groups are going to take the bulk of backfills.
  - Senior Engineers
  - Senior Staff
  
  Following that we will review what employees would be available for a mentorship program. We did this with the following code:
  
![Deliverable 2](https://user-images.githubusercontent.com/107363203/204175119-101434b1-1c24-4d76-a055-fdf830c47d15.png)

 
- We were then able to determine 1,549 available employees who were born after 1965.

![Filtered Unique Titles](https://user-images.githubusercontent.com/107363203/204175143-6f9b61aa-ef79-48d2-ac4f-a8b7bce3de7b.png)

- Engineers and Senior Staff will have the greatest impact on the mentorship program.

# Summary of Report

- How many roles will need to be backfilled after the "Silver tsunami" occurs?

   - Close to 72,000 roles will need to be replaced.

- Are there enough qualified, retirement ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

   - There are currently not enough employees for a one-on-one mentorship program. If this was split up into groups by department and titles for one individual to coach multiple people then it would work.
