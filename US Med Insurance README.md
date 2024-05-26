# U.S. Medical Insurance Costs

This project investigates a dataset of medical insurance costs, using Python to analyze and extract insights. The dataset, `insurance.csv`, includes information about patients' age, sex, BMI, number of children, smoking status, U.S. geographical region, and yearly medical insurance costs.

Key steps and analyses in the project include:

1. **Reading the Data**: 
   - The `read_csv_to_dict` function reads the CSV file and organizes the data into corresponding lists for each attribute.

2. **Average Insurance Cost**:
   - The `average_cost` function calculates the average yearly insurance cost across all patients.
   - The result is formatted in an accounting style for clarity.

3. **Average Age of Patients**:
   - The `average_age` function computes the average age of patients in the dataset.

4. **Sex Distribution Analysis**:
   - The `analyse_sex` function counts and compares the number of female and male patients.

5. **Regional Population Analysis**:
   - The `populated_region` function identifies the most and least populated U.S. regions among the patients.

The results provide insights into average insurance costs, patient demographics, and regional distributions, offering a comprehensive overview of the dataset.
