# Emergency Room Dashboard

## Dashboard Link
https://app.powerbi.com/links/Oep7ZeS9BD?ctid=0bc92751-071a-4e2c-a48b-633206fef374&pbi_source=linkShare&bookmarkGuid=5a30c891-03b2-4a39-a5d9-92f1c3cf0662

## Problem Statement
This dashboard provides valuable insights into emergency room (ER) operations, helping healthcare administrators monitor patient flow, satisfaction levels, and average waiting times. By analyzing key metrics such as patient visits, demographics, satisfaction scores, and department-specific wait times, hospitals can enhance patient experience, optimize resource allocation, and reduce bottlenecks in emergency care.

Since the **average satisfaction score is 5** and **waiting time is approximately 35 minutes**, there is room for improvement in ER efficiency and patient care. Additionally, patient distribution by department and demographic factors helps pinpoint areas that need attention.

---

## Steps Followed

### **Data Preparation & Processing**
- **Step 1:** Imported hospital patient visit data (CSV) into **Power BI Desktop**.
- **Step 2:** Cleaned and processed data in **Power Query Editor**:
  - Checked column distributions, missing values, and data consistency.
  - Profiled data on the entire dataset.
  - Handled missing values (e.g., ensuring null values in satisfaction scores and waiting times are managed).

### **Dashboard Design & Visualizations**
- **Step 3:** Selected a professional **theme** for the report in **Report View**.
- **Step 4:** Created **key performance indicators (KPIs)**:
  - **Total Patients Visited** (Card Visual).
  - **Average Satisfaction Score** (Card Visual).
  - **Average Waiting Time** (Card Visual).
- **Step 5:** Developed **time-series analysis**:
  - Patient visits across different **days of the week** categorized by **gender** (Line Chart).
- **Step 6:** Implemented **patient demographics visualization**:
  - **Patients by Age Group** (Bar Chart).
  - **Satisfaction Scores by Race** (Table with star rating visuals).
- **Step 7:** Designed **department performance analysis**:
  - **Patients Visited vs. Satisfaction Scores by Department** (Line Chart).
  - **Department Referral & Average Waiting Time** (Table).
- **Step 8:** Added interactive **filters & slicers**:
  - Filters for **Gender, Race, and Age Group** to analyze patient trends.
  - Filters for ** Month and Year** to analyze trends for every month to monitor progress over months
- **Step 9:** Customized **dashboard elements**:
  - Added hospital branding: **logo, header text, and themed visuals**.
- **Step 10:** Published the report to **Power BI Service** for easy accessibility.

---

## Insights & Findings

### **1. Patient Flow & Satisfaction**
- **Total Patients Visited:** **450-550**.
- **Average Satisfaction Score:** **4-5.5** *(Improved by 7.8% from last month)*.
- **Average Waiting Time:** **35.11 minutes** *(Slight decrease of 0.3% from last month)*.

### **2. Patient Demographics & Trends**
- **Patients by Age Group:**
  - **Adults** have the highest ER visits.
  - **Elderly patients** make up a significant portion.
  - **Children** have the least number of visits.
- **Gender Trends:** Male and female patient visit rates are nearly balanced, with fluctuations during the week.
- **Satisfaction Scores by Race:**
  - **Pacific Islanders (6.46)** and **multi-racial patients (5.56)** reported the highest satisfaction.
  - **Native American/Alaska Native (3.60)** had the lowest satisfaction.

### **3. Department Performance & Wait Times**
- **Department with the Shortest Wait Time:** **Renal Department (29.57 mins)**.
- **Department with the Longest Wait Time:** **Cardiology (38.67 mins)**.
- **Patient Visits by Department:**
  - **General Practice & Orthopedics** have the highest patient volumes.
  - **Gastroenterology has the highest satisfaction** scores.

---

## Actionable Recommendations
✔ **Reduce ER waiting time:** Focus on optimizing high-wait-time departments like **Cardiology & Physiotherapy**.  
✔ **Improve patient experience:** Address concerns from **lower satisfaction racial groups** by evaluating their ER experience.  
✔ **Manage peak hours:** Identify **busy days (Monday & Saturday)** and allocate resources efficiently.  
✔ **Enhance ER efficiency:** Reduce patient backlogs by improving workflow in **high-traffic departments** like 'None' Depratment.  

---

This **Emergency Room Dashboard** is a **powerful tool** for monitoring **hospital performance**, improving **patient satisfaction**, and enhancing **operational efficiency**. 🚑📊
