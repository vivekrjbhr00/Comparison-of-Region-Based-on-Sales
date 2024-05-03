# Comparison of Region Based on Sales

Description

The director of a leading organization wants to compare the sales between two regions. He has asked each region operators to record the sales data to compare by region. The upper management wants to visualize the sales data using a dashboard to understand the performance between them and suggest the necessary improvements.

 

Objective: Help the organization by creating a dashboard to visualize the sales comparison between two selected regions.

Datasets: Sample Superstore

 

#  Steps to Perform: 

1. Select Sample Superstore as Dataset.
   
   a. Use Sample Superstore Dataset
   
    b. Select Data
   
    c. Use Group by from Data Source Table on a Folder to create a folder to segregate the required data for Customer Name and Order ID inorder to organize the data thoroughly

2. Create a hierarchy called Location for the variable Country.
   
3. Create two parameters: Primary Region and Secondary Region with all regions listed in them. Here, primary and secondary region are the two regions where the sales are being compared.


   a. Create Parameters for Primary Region and Secondary Region


    b. Create a Calculated Field for both Primary Region and Secondary Region

5. Create a First Order Date

    a. Create a Calculated Field and name it as the First Order Date

7. Create a dashboard

    a. Align all sheets in the dashboard

9. Partition the dashboard to display the below details of Primary Region and Secondary Region

   a. First Order Date

   b. Total Sales

   c. Average Sales per Order

   d. No. of Customers

   e. No. of Products in Sale
