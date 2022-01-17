# Kickstarter-Analysis
This is a quick view of demonstrating of Excel skills.

## Overview of Project

## Purpose
The purpose of this project is to demonstrate a quick view of my mastered Excel skills within this program. Excel is a powerful tool that can be used across all Organizations areas, including personal budgeting to complex financial analysis. Using Excel data, I have learnt to organize, filter and sort data using advanced formulas and by creating interactive charts, Pivot tables and graphs. I was able to make meaningful interactive charts for presentations.  

## Analysis and Challenges

Here's a quick look at the Kickstarting Analysis and Challenges of this Project, including the following tasks:

-	Import data into a table for analysis.
-	Apply filters, conditional formatting, and formulas.
-	Generate and interpret pivot tables.
-	Calculate summary statistics such as measures of central tendency, standard deviation, and variance.
-	Characterize data to identify outliers in datasets.
-	Perform an Excel analysis with visualizations.
-	Interpret common Excel visualizations

## Our Challenge Data Background

Louise wants to start a crowdfunding campaign to fund her play Fever, in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals. Using the Kickstarter dataset, we’ll visualize campaign outcomes based on their launch dates and their funding goals. And then to create a written report based on the analysis and the visualizations.





## Conditional Formatting
### Applied the Conditional Formatting and color coded based on its cell value. This gave a clear quick view of Successful, Canceled, Live and Failed outcomes at a glance to the viewers. 

 ![image](https://user-images.githubusercontent.com/90879122/149717702-2154c1a6-3e03-4058-b283-9b65165020d6.png)

## Calculated the Average Donations
### This gave a quick view of percentage; how much money people have pledged to campaigns historically.

![image](https://user-images.githubusercontent.com/90879122/149717836-b8aea8c4-a92a-4d59-aecb-8a34380eb7b1.png)


## Analysis of Outcomes Based on Launch Date

### Deliverable Requirements with detail analysis:

### 1. A Years column is created based on the Date Created Conversion column in the Kickstarter spreadsheet.

Created "Years" column, used the YEAR() function to extract the year from the “Date Created Conversion” column.

![image](https://user-images.githubusercontent.com/90879122/149718266-7582ffd7-0f53-4a1b-83f8-bac36cd9bd28.png)


### 2. A pivot table is created in a new worksheet labeled "Outcomes Based on Launch Date".

Created a pivot table using the Kickstarter worksheet, and placed the pivot table in a new sheet. The pivot table filters on "Parent Category”, “Years" and view by Month.
 
![image](https://user-images.githubusercontent.com/90879122/149718328-10eab657-f4d4-4d36-a4f8-e24d79c20690.png)

 ![image](https://user-images.githubusercontent.com/90879122/149718349-904ac4ad-eaf2-499c-a815-bb5f4ed8a8bc.png)


### 3. The "Parent Category" is filtered on "theater".

![image](https://user-images.githubusercontent.com/90879122/149718408-0b23777b-ccfe-4f7e-849e-6d1e8864b14a.png)

### 4. A line chart is created with the help of the Pivot table showing the number of successful, failed, or canceled projects by month.

This helps to visualize the relationship between outcomes and launch month. The current chart is filtered to Theater and the row labels are set to display the months of the year, and the campaign outcomes are sorted in descending order.

Grouping data in a PivotTable can help you show a subset of data to analyze. For example, view list of dates or times (date and time fields in the PivotTable) into quarters and months, etc.

![image](https://user-images.githubusercontent.com/90879122/149718497-56e28456-24a7-45e0-90f0-76523abf2dd6.png)

 

### Analysis of Outcomes Based on Goals

### Deliverable Requirements with detail analysis:

1.	A new sheet is created with the goal range from $1000 – $50000 with percentage of each category, so projects can be grouped based on their goal amount. With the use of COUNTIFS() function populated the “Number Successful," "Number Failed," and "Number Canceled" columns by filtering on the Kickstarter "outcome" column, on the "goal" amount column. Using the ranges created the "Subcategory" column using "plays" as the criteria.
2.	Populated the “Total Projects” column with the number of successful, failed, and canceled projects for each row.

 ![image](https://user-images.githubusercontent.com/90879122/149718616-8a8a8258-3482-4c10-b033-ec2c6b09e8fa.png)


4. The percentages of successful, failed, and canceled projects are calculated based on the data from the "Total Projects," "Number Successful," "Number Failed," and "Number Canceled" columns.
 ![image](https://user-images.githubusercontent.com/90879122/149718656-039e4f05-2f09-4743-a5f4-59a331aac77e.png)

5. A line chart is created titled “Outcomes_vs_Goals” to visualize the relationship between the goal-amount ranges on the x-axis, the percentage of successful, failed, or canceled projects on the y-axis.
![image](https://user-images.githubusercontent.com/90879122/149718697-90ab678c-bd24-4ebc-bdf6-729a2b06e483.png)
 
## Challenges and Difficulties Encountered
Biggest challenge was filtering the pivot table to visualize the relationship between parent category and years, adding the correct dataset into the Columns, Rows and Values.

Another challenge for me was to master the =COUNTIFS()

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
- 
As Conclusions, our Line charts reflect that the months of May and June both have a greater success rate. A Line graph is useful to in showing the trends clearly. A bar graph wouldn't be able to convey this information in the same manner.

![image](https://user-images.githubusercontent.com/90879122/149718847-4346fefe-ac4c-479a-93d7-901b96338805.png)

 
-	What can you conclude about the Outcomes based on Goals?
As Conclusion, our Outcomes based on Goals measures using line chart of central tendency work in practice help us visualize the relationship between the goal-amount and percentage of each. It also helps finding the mean and median for each dataset's (the failed and successful campaigns).
 
![image](https://user-images.githubusercontent.com/90879122/149718916-fa7ae237-1b51-4602-b4e3-9dd79b344fde.png)

- What are some limitations of this dataset?
 
Some limitation can be that would have been helpful to know the deviations from the actual dataset.

-	What are some other possible tables and/or graphs that we could create?

•	Box Plots
•	Pie Graph
•	Column Graph
•	Area Graph
•	Scatter Graph
