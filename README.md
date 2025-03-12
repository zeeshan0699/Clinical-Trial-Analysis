# **Clinical Trials Data Analysis & Dashboard Report**  

## **Project Overview**  
This project was designed to analyze and visualize clinical trial data, identifying key trends in trial phases, medical conditions, sponsors, and patient enrollment. The primary objective was to develop an **interactive Power BI dashboard** that allows users to dynamically explore and extract insights from the dataset.  

The project was executed in three primary stages:  
- **Data Cleaning & Preparation**: Used Python libraries (**Pandas, NumPy**) to clean, structure, and preprocess the data.  
- **Exploratory Data Analysis (EDA)**: Conducted a detailed analysis to identify patterns, outliers, and key trends.  
- **Dashboard Development in Power BI**: Designed and implemented an interactive dashboard with dynamic filtering and visualization features.  

This dashboard serves as a **decision-making tool for pharmaceutical companies, researchers, and policymakers**, enabling efficient analysis of industry trends.  

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
- Built a **pie chart of top sponsors**, showing that **major pharmaceutical companies (Pfizer, Novartis, Merck, Roche)** drive most of the research.  

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

### **Trends in Clinical Trials Over Time**  
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
- The **top sponsors** are large pharmaceutical companies, with **Pfizer, Novartis, Merck, and Roche** leading in trial numbers.  
- Suggests that **private industry investment** is a major driver of clinical research.  

These insights were validated through **statistical and visual analysis**, guiding the dashboard’s design.  

## **Dashboard Design & Visualization (Power BI)**  
![image](https://github.com/user-attachments/assets/60309fcb-b100-4a82-9d4b-6bbffb1b5b7e)

The Power BI dashboard was structured to ensure **clarity, interactivity, and ease of navigation**.  

### **Key Dashboard Features**  
- **Line Chart**: Trends in clinical trials over time.  
- **Bar Chart**: Top 10 medical conditions by trial count.  
- **Pie Chart**: Distribution of trial sponsors.  
- **KPI Cards**: Total enrollment and trial count metrics.  
- **Filters & Slicers**: Enable dynamic data exploration.  

To maintain **visual consistency and readability**, a **clean and professional color scheme** was selected. The layout was designed to **avoid clutter** while enabling users to explore different dimensions efficiently.  

## **Insights from the Dashboard**  

### **Trends in Clinical Trials Over Time**  
- Clinical trials **peaked between 2000 and 2010**.  
- A decline post-2010 suggests **increasing regulatory or financial barriers** affecting trial initiation.  

### **Most Researched Medical Conditions**  
- **Diabetes, Cancer, and Hypertension** dominate research.  
- Indicates a global focus on **chronic disease management and treatment advancements**.  

### **Clinical Trial Phase Distribution**  
- **Phase 3 trials** are the most common, highlighting the importance of **efficacy validation before approval**.  
- The **low number of Phase 4 trials** suggests **a gap in post-market drug monitoring**, which could be an area for further exploration.  

### **Top Sponsors in Clinical Research**  
- **Pfizer, Novartis, Merck, and Roche** are the primary industry players.  
- Emphasizes the **strong role of private funding in drug development**.  

## **Exploration & Future Analysis**  

The dashboard enables users to explore multiple dimensions of clinical trials:  
- **Analyze historical trends** to assess changes in trial activity.  
- **Filter trials by sponsor** to understand which organizations lead in research.  
- **Examine enrollment patterns** to identify fluctuations in patient recruitment.  
- **Compare trial phases** to assess industry focus areas.  

### **Future Enhancements**  
- **Analysis of trial success rates** to determine which sponsors and conditions yield the highest approval rates.  
- **Correlation between trial funding and success outcomes** to assess the impact of financial investment on research breakthroughs.  
- **Tracking emerging trends in clinical trials** by analyzing shifts in focus areas, such as new disease categories or treatment types.  

## **Conclusion**  

This project successfully combined **Python for data preparation and analysis with Power BI for visualization**, resulting in a dynamic and insightful clinical trials dashboard.  

- **Data cleaning & preparation** ensured high-quality insights.  
- **Exploratory Data Analysis (EDA)** provided a deeper understanding of industry trends.  
- **Power BI dashboard** enables **interactive exploration of key clinical trial metrics**.  

The dashboard serves as a valuable tool for **pharmaceutical companies, researchers, and policymakers**, helping them **track industry trends, allocate resources effectively, and make data-driven decisions**.
