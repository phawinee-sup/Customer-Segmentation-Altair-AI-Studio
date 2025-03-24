# Data Preparation for Customer Segmentation

## Overview
This project focuses on preparing data for customer segmentation, specifically analyzing customers' payment behaviors in relation to their due dates. The goal is to create a process that computes various attributes to understand how early or late customers tend to make payments. The dataset will be used to segment customers based on these behaviors.

## Instructions

### Task
1. **Create a process** to prepare the data for customer segmentation.
2. **Use the following attribute names** for each variable.
3. The output dataset should contain exactly **990 rows** of data.

### Attribute Names and Descriptions

1. **min_days_before**  
   - The minimum number of days a customer paid **before** the due date.

2. **max_days_before**  
   - The maximum number of days a customer paid **before** the due date.

3. **avg_days_before**  
   - The average number of days a customer paid **before** the due date.

4. **min_days_after**  
   - The minimum number of days a customer paid **after** the due date.

5. **max_days_after**  
   - The maximum number of days a customer paid **after** the due date.

6. **avg_days_after**  
   - The average number of days a customer paid **after** the due date.

7. **percent_before**  
   - The percentage of times a customer paid **before** the due date.

8. **percent_ontime**  
   - The percentage of times a customer paid **on time** (exactly on the due date).

9. **percent_after**  
   - The percentage of times a customer paid **after** the due date.

### Notes
- The data should be **accessed from a database system**.
- Ensure that the final dataset contains exactly **990 rows**.

## How to Run the Process in Altair AI Studio

1. **Import the Process File**  
   - In **Altair AI Studio**, open your workspace.
   - Import the **.rmp** process file that contains the workflow for data preparation.

2. **Set up the Database Connection (if necessary)**  
   - If the data is coming from a database, configure the connection settings within Altair AI Studio:
     - Go to **Settings** → **Database Connections**.
     - Enter the necessary credentials and connection details for your database (e.g., host, username, password, database name).

3. **Run the Process**  
   - Once the process file and database connection are properly set, run the process by clicking **Run**.
   - The process will automatically calculate the attributes for customer segmentation and prepare the dataset.

4. **Check the Output**  
   - Ensure the resulting dataset contains exactly **990 rows**.
   - You can check the output in the **Data** panel within Altair AI Studio.

5. **Save and Export the Process**  
   - After running the process, you can save the results or export the dataset for further analysis.
