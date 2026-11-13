# Healthcare-Data-Analysis-and-Informatics
This is the module end assignment.This project aims to analyze a comprehensive healthcare dataset  comprising medical examinations, hospitalization details, and customer profiles to extract  insights into patient health profiles, medical histories, and healthcare costs.
# # Data Cleaning:  
# 1.Missing value - =countif (G2:G244,"~")
# 2.missing value Month =if(C2="2","SEP",C2).Year=if(B2="?",Average($B$2:$B$2344),B2
# 3.missing value -find most frequent value =countif(H2:H2336,H2),=countif(H2:H2336,H2336)get "NO".hospital tier=countif(G2:G2344,G241),=countif(G2:G2344,G2),=countif(G2:G2344,G6)get tier-2. city tier =countif(H2:H2344,H3),=countif(H2:H2344,H20)=countif(H2:H2344,H7),get-tier2
# 4. mising value state ID =if(I2="?","Unknown",I2)
# # Data Transformation:
# 1.Split the “Customer Names”Table into : ‘Title’, ‘First Name’, and ‘Last Name’. using text to column and flashfill.
# 2.Convert the "NumberOfMajorSurgeries" column to replacing non-numeric characters using find and replace , replace with "0".
# 3.Check for inconsistencies in the 'Heart Issues'=proper(D2:D2336) and'smoker'==proper(I2:I2336)
# 4. Weight Status=ifs(B2<18.5,"Underweight",B2<25,"Normal Weight",B2<30,"Overweight",B2>30,"Obesity" 
# 5.Diabetes Status =ifs(D2<5.7,"Normal",D2<6.5,"Prediabetes",D2>6.5,"Diabetes" 
# 6.‘Date of Birth’ and format =Concatenate(D17,"-",C17,"-",B17)
# 7.Calculate the ‘Age’ =2023-Year(B2)
# 8.Format ‘charges’ column as currency ($) General-currency
## Data Exploration, Analysis & Visualization
Create pivot tables ,using Pie/Donut ChartColumn/Bar Chart, Line chart and created Dashboard.
