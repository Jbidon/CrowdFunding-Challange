# Homework1
Challenge 1
Used conditional formatting to fill each cell in the "outcome" column with a different color, depending on whether the associated campaign was successful, failed, canceled, or is currently live.
Created a new column called "Percent Funded" that uses a formula ("pledged" column / "goal" column) to find how much money each campaign made relative to its initial funding goal.
Utilized conditional formatting to fill each cell in the "Percent Funded" column according to a three-color scale. The scale starts at 0 with a dark shade of red, transitions to green at 100, and blue at 200.
Created a new column called "Average Donation" that uses a formula to find how much each project backer paid on average. Followed by 2 other columns, "Parent Category" and "Sub-Category", that uses formulas to split the "Category and Sub-Category" column into their own.
Created a new worksheet called "Parent Category Success" with a pivot table that analyzes the initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category. Paired that with a stacked-column pivot chart that can be filtered by country based on the table.
Created another new sheet called "Sub-Ctegory Success" with a pivot table that analyzes the initial worksheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category. Also paired this one with a stacked-column pivot chart that can be filtered by country and parent category based on the table.
Created two new columns called "Date Created Conversion" and "Date Ended Conversion" and applied the formula =(((J2/60)/60)/24)+DATE(1970,1,1) for column S and formula =(((K2/60)/60)/24)+DATE(1970,1,1) for the column T.
Created a new worksheet called "Monthly Success" with a pivot table that has a column of "outcome", rows of "Date Created Conversion", values based on the count of "outcome", and filters based on "parent category" and "Years". I paired this with a pivot-chart line graph that visualizes this table.
Created a another worksheet called "Goal Analysis" utilizing data from the following columns: "Goal", "Number Successful", "Number Failed", "Number Canceled", "Total Projects", "Percentage Successful", "Percentage Failed", and "Percentage Canceled"
