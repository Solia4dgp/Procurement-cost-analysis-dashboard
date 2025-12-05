# Procurement_dashboard
Executive dashboard for analyzing procurement and supplier performance

## Table of content
- [Project overview](#Project_overview)
- [Data cleaning and preparation](#Data_cleaning_and_preparatio)
- [Dashboard pages](#Dashboard_pages)
- [Key findings](#Key_findings)
- [Recommendations](#Recommendations)
- [Limitations](#Limitations)
## Project overview
This repository contains the cleaning steps and visualization files for a procurement & cost analysis dashboard. The goal is to provide an executive overview while offering deep dives into the supplier performance, item level detail, buyer activity and category analysis.

## Data cleaning and preparation
1. The data was initially loaded from a csv file into power bi desktop.
2. The first row of data was promoted to become the column names.
3. The month coloumn was sorted into an alphabetical order

## Dashboard pages 
- Executive overview
  
  High-level summary of total cost, top suppliers and monthly spending trends.<img width="628" height="319" alt="Screenshot (236)" src="https://github.com/user-attachments/assets/0aaf4e36-618c-4f10-943f-5d82635613fd" />




- Supplier performance analysis

  Ranks suppliers by total amount spent, order volume and calculation of average cost per item per supplier.
<img width="645" height="365" alt="Screenshot (189)" src="https://github.com/user-attachments/assets/ff7dd555-2c11-4098-88e5-bb26a2e3ddb3" />
<img width="645" height="250" alt="Screenshot (190)" src="https://github.com/user-attachments/assets/3171b2ff-b2d5-4462-9801-912951f23fe2" />


- Category performance analysis

  Compares total cost, average cost and purchase volume across all product categories.
<img width="355" height="250" alt="Screenshot (147)" src="https://github.com/user-attachments/assets/df2d149d-f1cc-4231-bdc5-203cf4c244fb" />

- Item level detail:

Pinpointing top-performing items and pricing analysis.
<img width="664" height="380" alt="Screenshot (191)" src="https://github.com/user-attachments/assets/c33fbd06-c72b-4fe5-bbe2-466d7116ff31" />

- Buyer activity

   Analyzes spending patterns by individual buyers based on expenditure and purchase diversity.
<img width="611" height="356" alt="Screenshot (192)" src="https://github.com/user-attachments/assets/b7083b38-f370-44eb-b21e-f01d54bf34f3" />

🔬Key findings 

1. High-value concentration
   
Category Spend Concentration: Electronics and Software are the dominant cost drivers, accounting for over 70% of the total cost. 

Supplier risk/leverage: TechMart Inc. is the single largest supplier by cost. This suggests maximum leverage for negotiating discounts but also a significant supplier concentration risk if TechMart Inc. experiences a supply disruption.

2. Operational efficiency & control
   
Positive spending trend: The monthly spending trend shows a general downward trajectory over the year.

Purchase velocity: The high volume of orders relative to the total cost suggests a relatively high frequency of low-value transactions.

🚀 Recommendations 
1. Strategic sourcing focus
   
Initiate strategic sourcing: Launch immediate, high-priority sourcing projects for Electronics and Software. 

Mitigate supplier risk: Develop a secondary supplier for key items purchased from TechMart Inc. to reduce dependency.

2. Process and compliance improvement
   
Implement compliance training: Use the Buyer Activity dashboard to identify the top 10 buyers with the highest non-compliant or diverse spending. Implement an e-procurement system for quick, compliant purchases.

🚧 Limitations 
1. Data quality and scope

Limited supplier risk data: The dashboard focuses purely on cost. It does not include critical non-financial KPIs such as on-time delivery rate, supplier quality score (defect rate), or financial stability data, all of which are vital for a complete risk assessment.

2. Technical and operational
   
Spend classification: The accuracy of the category findings is entirely dependent on the quality of the initial data cleansing and classification 

For a full breakdown and executive insights, check out the 4-part LinkedIn series

Supplier performance analysis: https://www.linkedin.com/posts/aileru-solia-471407285_supplierperformance-procurementanalytics-activity-7401517908394221568-Zp2O?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEVLMdUBDlhp6fhuqXMKrvomaXej1w4FXQI

Category performance analysis: https://www.linkedin.com/posts/aileru-solia-471407285_categoryanalysis-spendoptimization-procurementstrategy-activity-7401885658711019520-ySCf?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEVLMdUBDlhp6fhuqXMKrvomaXej1w4FXQI

Item level detail and buyer activity: https://www.linkedin.com/posts/aileru-solia-471407285_procurement-costanalysis-datadrivendecisions-activity-7402267163644035072-W7dd?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEVLMdUBDlhp6fhuqXMKrvomaXej1w4FXQI

Executive overview: https://www.linkedin.com/posts/aileru-solia-471407285_procurement-costanalysis-spendanalytics-activity-7402649531382648832-qp12?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEVLMdUBDlhp6fhuqXMKrvomaXej1w4FXQI
