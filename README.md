# Unveiling Aviation Safety: A Visual and Interactive Exploration of Accident Data

## **Project Overview**
This project, part of the **CSC 805 Data Visualization** course at **San Francisco State University** (SFSU), is focused on creating an interactive platform to visualize aviation accident data. Our goal is to uncover insights into the complex factors that contribute to aviation accidents, providing a visual and interactive way to explore these patterns. Through this project, we aim to highlight safety improvement areas and uncover hidden risks in aviation.

The project utilizes advanced data visualization techniques to analyze the **Aviation Accident Database** provided by Kaggle, focusing on key questions around accident distribution, aircraft categories, injury severity, and trends over time.

## **Project Details**
**Course**: CSC 805 – Data Visualization  
**Instructor**: Dr. Shahrukh Humayoun  
**Semester**: Fall 2024  
**Department**: Computer Science, San Francisco State University  

### **Key Objectives:**
1. Distribution of accident causes by phase of flight (takeoff, cruise, landing) and aircraft category.
2. Relationship between weather severity and injury severity, segmented by aircraft category.
3. Trends in accident frequencies over the years for specific aircraft models.
4. Distribution of accident damage based on flight purpose (Personal, Business, Scheduled).
5. Identification of safety improvement areas based on data trends, accident types, and contributing factors.

## **Dataset Description**
The project utilizes two primary datasets:
1. **AviationData.csv**: Contains detailed accident data, including aircraft categories, injury types, contributing factors (weather, phase of flight), and trends in accidents over time.
2. **USState_Codes.csv**: Provides a mapping of U.S. states to their respective abbreviations.

### **Data Source**: 
Aviation Accident Database & Synopses (Kaggle, up to 2023)

## **System Architecture**
The architecture for this project follows these steps:

1. **Data Acquisition**: The dataset is acquired from Kaggle, providing a foundation for analysis.
2. **Data Preprocessing with Pandas**: The data is cleaned, transformed, and structured using Python’s Pandas library to ensure its quality and readiness for visualization.
3. **Visualization in Tableau**: After preparing the data, it is exported to Tableau, where interactive dashboards and charts are developed.

## **Dashboards and Visualizations**

### **1. Global Accidents and Fatalities Overview**
- **Purpose**: Provides a high-level summary of global accident trends and fatalities from 1981 to 2022.
- **Visualizations**:
  - Trend of total accidents vs fatalities over time.
  - Region-wise accident distribution (pie chart).
  - Global map visualizing accident and fatality distribution by country.

[View Dashboard](https://public.tableau.com/views/AviationCrashAnalysis_17329992895540/GlobalAccidentsandFatalitiesOverview?:language=en)

### **2. Aircraft Category and Flight Phase Analysis**
- **Purpose**: Analyzes accidents based on aircraft categories and phases of flight (e.g., landing, cruising, take-off).
- **Key Insights**:
  - "Airplane" accidents are most frequent.
  - "Landing" phase has the highest frequency of accidents.

### **3. Accident Impact by Purpose and Injury Severity**
- **Purpose**: Explores the distribution of accidents by flight purpose (personal, business) and injury severity.
- **Key Insights**:
  - Most accidents occur in "Personal" flights, with "Non-Fatal" injuries being the most common.

### **4. Weather Conditions and Injury Severity Trends**
- **Purpose**: Analyzes the effect of weather conditions (VMC, IMC) on injury severity.
- **Key Insights**:
  - Weather-related accidents, particularly in IMC, show a strong correlation with higher injury severity.

### **5. Accidents by Schedule and Engine Type**
- **Purpose**: Investigates the relationship between flight schedules (scheduled vs non-scheduled) and engine types in accident data.

---

## **Project Contributors**

| **Team Member**                | **Role**            |
|---------------------------------|---------------------|
| **Dhvanil Bhagat**              | Data Analyst        |
| **Divya Panchal**               | Data Visualization Specialist |
| **Chetas Nikunjbhai Parekh**    | Team Lead & Data Visualization Specialist |

---

## **Demo Video**
A demo of the project showcasing the interactive visualizations is available:

[View Demo Video](https://drive.google.com/file/d/1rghjGGmurFohOwY-Tr5FdLozjmNrBgGl/view?usp=sharing)

---

## **Conclusions and Insights**
Through this project, we have explored trends and patterns in aviation accident data, identifying key factors that contribute to accidents and injury severity. The interactive visualizations help convey complex data in an easily understandable format, offering valuable insights into improving aviation safety.

By visualizing data on accident severity, aircraft types, flight phases, and weather conditions, we aim to raise awareness and support policy changes, technological advancements, and pilot training improvements to enhance aviation safety.
