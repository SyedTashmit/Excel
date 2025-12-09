# Introduction To Excel 

For this project, I have explored the basic functions of Microsoft Excel including filtering, SUM, AVERAGE, MAX and conditional formatting.

This document outlines the tasks completed on the retail_sales_dataset.xlsx Excel file. The dataset contains information on retail sales, including customer age, sales figures, commissions, and other relevant metrics. 
Below are the steps to show how the data has been analysed.

## Tasks

1. To add all available data between columns A – H into a ‘table’ 
   <img width="618" height="355" alt="image" src="https://github.com/user-attachments/assets/085cf9f7-b3d7-43db-95fe-2121ff69810c" />


2. Using the filter function.
<img width="432" height="611" alt="Table 2" src="https://github.com/user-attachments/assets/5cea33ad-691e-4509-8e3e-5704a5700912" />


3. Using the ‘SUM’ function to show the total commission in the cell "P10"
   Formula : =SUM(H2:H100)
<img width="610" height="219" alt="image" src="https://github.com/user-attachments/assets/f5468486-ecd0-4dd4-a9a4-e889bc76d1a2" />   


4. Using the ‘AVERAGE’ function to show the average commission in cell "P11"
   Formula: =AVERAGE(H2:H100)
   <img width="611" height="262" alt="image" src="https://github.com/user-attachments/assets/b813cd8f-5b8f-414a-bafc-b7f28e4afc5a" />

 5. I also used "VLOOKUP" to retrieve the commission for a specific customer ID.
     Formula: =VLOOKUP(J2, A:H, 8, FALSE)

    By uing filters and dynamic functions such as UNIQUE, SUMIFS, and AVERAGEIFS improves efficiency and insight when analysing data.

    
