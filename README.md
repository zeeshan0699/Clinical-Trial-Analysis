# **Clinical Trials Data Analysis & Dashboard Report**  

## **Project Overview**  
This project analyzes clinical trial trends, sponsor contributions, and patient enrollment patterns using data from **Aero Data Lab**. The objective is to uncover insights into trial success rates, phase distribution, and research focus areas through an interactive Power BI dashboard.


The project was executed in three primary stages:  
- **Data Cleaning & Preparation**: Used Python libraries (**Pandas, NumPy**) to clean, structure, and preprocess the data.  
- **Exploratory Data Analysis (EDA)**: Conducted a detailed analysis to identify patterns, outliers, and key trends.  
- **Dashboard Development in Power BI**: Designed and implemented an interactive dashboard with dynamic filtering and visualization features.  


## **Project Goals and Achievements**  

### **Identifying Trends in Clinical Trials Over Time**  
- Conducted a **historical analysis** of trial data and plotted time-series trends.  
- Identified a significant **increase in clinical trials between 2000 and 2010**, followed by a decline post-2010.  

### **Analyzing Medical Conditions Under Research**  
- Filtered and visualized **the top 10 most researched medical conditions**.  
- Found a strong focus on **chronic diseases such as Diabetes, Breast Cancer, and Hypertension**.  

### **Understanding Trial Distribution Across Phases**  
- Developed a bar chart showing **the distribution of trials across different phases**.  
- Identified that **Phase 3 trials dominate**, while **Phase 4 trials are significantly fewer**, indicating limited post-market studies.  

### **Assessing Leading Sponsors of Clinical Trials**  
- Built a **pie chart of top sponsors**, showing that **major pharmaceutical companies (GSK, Novartis, Pfizer, Merck)** drive most of the research.  

### **Examining Patient Enrollment Trends**  
- Created **key performance indicators (KPIs)** to analyze total patient enrollment.  
- Established a direct correlation between the **number of trials and patient recruitment trends**.  

### **Developing an Interactive Dashboard**  
- Implemented **filters, slicers, and navigation buttons** in Power BI for enhanced usability.  
- Designed a structured, visually appealing layout to **support decision-making and exploration**.  

## **Data Cleaning & Preparation (Python)**  
Before visualization, the dataset was cleaned and preprocessed to ensure accuracy. Key steps included:  

- **Handling Missing Data**: Missing values in trial phases and enrollment fields were imputed using statistical techniques.  
- **Removing Duplicates**: Eliminated redundant records to prevent distortion.  
- **Data Type Conversion**: Standardized date formats and categorical fields for consistency.  
- **Filtering & Aggregation**: Extracted relevant subsets, aggregated totals, and structured enrollment data by year.  

This structured approach ensured a **high-quality dataset**, enabling meaningful insights in the Power BI dashboard.  

## **Exploratory Data Analysis (EDA) Insights**  

### **Trends in Clinical Trials and Patient Enrollment Over Time**  
- A **sharp rise in clinical trials between 2000 and 2010**, peaking at approximately **1,100 trials per year**.  
- A **decline post-2010**, likely due to **regulatory constraints, funding limitations, or shifting research priorities**.  

### **Top Medical Conditions Researched**  
- **Diabetes, Breast Cancer, and Hypertension** are the most frequently studied conditions.  
- Suggests a strong focus on **chronic diseases and high-mortality conditions**, aligning with healthcare priorities.  

### **Distribution of Clinical Trial Phases**  
Clinical trials are typically conducted in sequential phases, each serving a distinct purpose:  
- **Phase 1**: Small-scale safety studies (2,516 trials).  
- **Phase 2**: Early efficacy and dosage trials (3,596 trials).  
- **Phase 3**: Large-scale efficacy trials before regulatory approval (4,887 trials).  
- **Phase 4**: Post-market studies to monitor long-term safety (2,015 trials).  

- **Phase 3 trials dominate**, indicating a focus on **validating drug efficacy before approval**.  
- **Limited Phase 4 trials** highlight a gap in **long-term drug safety monitoring**.  

### **Leading Sponsors in Clinical Trials**  
- The **top sponsors** are large pharmaceutical companies, with **GSK, Novartis, Pfizer, and Merck** leading in trial numbers.  
- Suggests that **private industry investment** is a major driver of clinical research.  

These insights were validated through **statistical and visual analysis**, guiding the dashboard’s design.  

## **Dashboard Design & Visualization (Power BI)**  

![image](https://github.com/user-attachments/assets/f7266957-5733-4bd0-be7b-e8dc8c9e62e8)



The Power BI dashboard was structured to ensure **clarity, interactivity, and ease of navigation**.  

### **Key Dashboard Features**  
- **Line Chart** : Trends in clinical trials and patient enrollment over time.  
- **Bar Chart**  : Top 10 medical conditions by trial count.  
- **Pie Chart**  : Distribution of trial sponsors.  
- **KPI Cards**  : Total enrollment and trial count metrics.  
- **Gauges**     : Visual representation of trial success and dropout rates.  

To maintain **visual consistency and readability**, a **clean and professional color scheme** was selected. The layout was designed to **avoid clutter** while enabling users to explore different dimensions efficiently.  

## **Exploration & Future Analysis**  

The dashboard enables users to explore multiple dimensions of clinical trials:  
- **Analyze historical trends** to assess changes in trial activity.  
- **Filter trials by sponsor** to understand which organizations lead in research.  
- **Examine enrollment patterns** to identify fluctuations in patient recruitment.  
- **Compare trial phases** to assess industry focus areas.  

## **Conclusion**  

This project provides insights into clinical trial phases, sponsor influence, patient enrollment, and research trends. The Power BI dashboard serves as a tool for pharmaceutical companies, researchers, and policymakers to explore key metrics and make data-driven decisions. With further advancements in research funding and regulatory processes, trial success rates are expected to improve.

