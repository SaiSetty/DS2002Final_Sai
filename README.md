# DS2002Final_Sai
This is the repository for my final DS 2002 capstone project.    
There is a final_data folder that contains batch and stream data. This folder needs to be uploaded to DBFS in databricks before running the ipynb file in databricks.   
There is a classic_data_mart.sql file. This file needs to be imported and run in MySQL Workbench account connected to the ipynb file before running the ipynb file.   
There is a .ipynb file. This file is the main databricks notebook that has all the code to run the DS 2002 Final Project.   
**!!!Important Note:**  
The table output for *%sql SELECT * FROM fact_orders_silver* in section 6.2 shows all 2996 rows of data, so it might take a while to scroll. You can use *ctrl+f "%sql
DESCRIBE EXTENDED classicmodels_dlh.fact_orders_silver"* to skip to the next code block and avoid scrolling. Due to this large output it might also take a while to load directly on github so it might be easier to download the file.
