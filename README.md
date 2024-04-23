# Health_Campaign_HR_Analytics
England Rectifiers, a company in the UK recently organized a medical camp for their employee across the UK, across various states and cities. The health camp, conducted by a large hospital in London, compiled the data from the health camp, and shared it with the company. As an HR in the company, it is your job to analyze the employee data and present the state of employee health to your management.
Data Overview:
• Reg_code : Code of the region where health camp was organized
• Region : The state where the health camp was organized
• Area : City where the health camp was organized
• Avg_HCI: Average Healthcare index, calculated based on the vitals of each employee
• Average BP_Sys: Average Systolic Blood pressure of employees in given city
• Average BP_Dias: Average Disatolic Blood Pressure of employees in given City
• Height: Average height of employees in city (in meters)
• Weight: Average weight of employees in given city (in Kgs)
• Age: Average Age of employees in given City who attended the medical camp
• Male: Number of male employees who attended the camp in given city
• Female: Number of female employees who attended the camp in given city
Task:
As a data analyst for the England Rectifiers perform the below given task and present your analysis with the necessary interpretations.
1. Identify the three most common regions with the highest proportion of male employees
2. Create a new column ‘BMI’ in the data frame calculated as weight divided by the square of height and display the first five rows.
3. Create a new column ‘BMI Category’ based on BMI values:
- BMI lesser than 18.5 : Underweight
- BMI is between 18.5 and 25 : Normal
- BMI is between 25 and 30 : Overweight
- BMI greater than 30 : Obese
4. Calculate the average ‘Average HCI’ for each region
5. Find the region with the highest average ‘Average HCI’ and display the corresponding details
6. Calculate the average ‘Average HCI’ for employees aged between 30 and 40 in each region
7. Create a binary column High Blood Pressure indicating whether an employee has high Blood pressure if Average BP Systolic > 130 or Average BP Diastolic > 80.
8. Use the Average HCI as the target variable and build a linear regression model to predict the average HCI based on height, weight, male and female. Evaluate the model’s performance.
