# Excel_Healthcare_Analysis

**Project Overview**

This project focuses on analyzing healthcare data using Microsoft Excel to identify patterns in patient health conditions, healthcare charges, hospital characteristics, and demographic factors.
The project involved **data cleaning, data transformation, data consolidation, PivotTable analysis, data visualization, and interactive dashboard creation**.
The final outcome is an interactive Excel dashboard that allows users to explore healthcare outcomes and charges using different health-related filters.

**Project Objectives**

- Clean and preprocess healthcare datasets.
  
- Handle missing and inconsistent values.
  
- Transform raw patient information into analysis-ready data.
  
- Combine information from multiple datasets using **Customer ID**.
  
- Analyze healthcare charges based on different health conditions.
  
- Examine relationships between age and healthcare variables.
  
- Create PivotTables for summarized analysis.
  
- Build charts for visual interpretation.
  
- Develop an interactive dashboard using Excel slicers.

**Dataset**

The project uses three related datasets:

**1. Customer Names**

Contains customer identification and name information. Key fields involve Customer ID,Customer Name,Title,First Name,Last Name

**2. Medical Examinations**

Contains patient medical and health-related information.Key fields involve  Customer ID,BMI,HBA1C,Heart Issues,Any Transplants,Cancer History,Number of Major Surgeries,Smoker,Weight Status,Diabetes Status

**3. Hospitalisation Details**

Contains hospitalization and healthcare cost information. Key fields involve Customer ID, Year, Month, Date, Children, Charges, Hospital Tier, City Tier, State ID, Date of Birth, Age

**Data Cleaning**

The raw datasets were cleaned and prepared before analysis.

Missing Value Handling : Missing values represented by `?` were identified and handled according to the project requirements.

Data Standardization : Inconsistent categorical values were standardized.It is done using the PROPER()

**Data Transformation**

Weight status and Diabetes status was categorised with the given requirement.
Age was calculated using the patient's Date of Birth and the specified dataset collection date.

**Data Consolidation**

The three datasets were combined into a consolidated Healthcare worksheet.
Customer ID was used as the common key.
Excel lookup functions, particularly VLOOKUP, were used to retrieve information from the different datasets.

Exploratory Data Analysis : PivotTables were created to analyze important healthcare patterns and required visualisation charts were inserted accordingly.

**Dashboard Creation**

An interactive Excel dashboard was created to consolidate the major findings from the analysis.Two slicers of weight and diabetes status were added to make the dashboard interactive.These slicers allow users to explore healthcare outcomes and charges for different patient groups.

**Conclusion**

This project used Excel to clean, analyze, and visualize healthcare data. PivotTables, charts, and an interactive dashboard helped identify patterns in health conditions, healthcare charges, age, and hospital characteristics. Overall, the project demonstrates practical skills in data analysis, visualization, and dashboard creation using Excel.

