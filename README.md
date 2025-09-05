# Employee Data-Analysis-
This analysis was conducted using power bi focusing on the departmental analysis  of a employee dataset and to check the productivity and performance of various department and how it affects the general growth of the organization

# Employee Data Report

## Introduction
The employee data set is a comprehensive collection of information related to the workforce within an organization with focus being on departments.  
It provides valuable insights into various attributes such as employee IDs, names, job titles, departments, race description, performance score, gender code, date of birth, division, and business unit.  
These attributes characterize each employee, enabling effective human resource management and strategic decision-making.

---

## Objectives
- To analyze performance metrics in order to assess the effectiveness of each department.  
- To optimize staffing levels and budget allocation across departments to ensure efficient use of resources and minimize costs.  
- To identify high performing departments and develop targeted training and development for underperforming departments.  
- To identify skill gaps within departments to tailor training programs that enhance employee performance and career growth.  
- To evaluate the effectiveness of collaboration between departments to improve communication and teamwork.  
- To provide insights that inform strategic decisions regarding departmental restructuring, expansion, or resource reallocation.  

---

## Scope
This report specifically examines key variables including:  
- **Department Performance**: Evaluation of departmental efficiency based on employee metrics.  
- **Employee Turnover Rates**: Analysis of retention within departments.  
- **Workforce Planning**: Identifying staffing needs.  
- **Performance Reviews**: Tracking employee performance by department.  
- **Budgeting**: Allocating resources based on departmental needs.  

---

## Dataset Overview
- **Data Sources**: The data is sourced and collected from a reliable channel.  
- **Dataset Review**: The dataset contains **3000 rows**.  

### Key Columns
- **Employee ID**: Unique identifier for each employee.  
- **First Name / Last Name**: Employee’s full name.  
- **Department Type**: The department where the employee works (e.g., Admin Offices, Executive Offices, IT/IS, Production, Sales).  
- **Position/Title**: Job title of the employee.  
- **Email**: Employee’s work email address.  
- **Date of Birth**: Employee’s birth date.  
- **Division**: The employee’s division.  
- **State**: The employee’s state.  
- **Job Function Description**: Brief description of the job.  
- **Performance Score**: The evaluation score from performance reviews.  
- **Race Description**: Employee’s race (White, Hispanic, Black, Asian, Other).  

---

## Data Cleaning Process
1. **Removing duplicates** – Power Query was used to identify and eliminate duplicate rows.  
2. **Handling missing values** – Checked for null/blank values in critical columns.  
3. **Standardizing data formats** – Applied `TEXT()` for dates and `UPPER()` / `LOWER()` for text consistency.  
4. **Correcting data entry errors** – Fixed typos and inconsistencies using `SUBSTITUTE()`.  
5. **Filtering unnecessary data** – Removed irrelevant rows via filters.  

---

## Exploratory Data Analysis (EDA) & Visualization

### Employees Overview
- Total Employees: **3000**  
- Gender Distribution: **1682 females (56%)** and **1318 males (44%)**

<img width="935" height="120" alt="Screenshot 2025-09-05 194347" src="https://github.com/user-attachments/assets/37bb0cb2-1ba9-4dc4-b5e3-0b380232c99f" />

### Department Overview
- **Admin Offices**: 80 employees (44F, 36M) across 19 divisions.

<img width="907" height="96" alt="Screenshot 2025-09-05 194535" src="https://github.com/user-attachments/assets/348854b9-455f-4a8d-9547-7557c2a4bafb" />
 
- **Executive Office**: 24 employees (1F, 23M) across 12 divisions.

    <img width="912" height="97" alt="Screenshot 2025-09-05 194904" src="https://github.com/user-attachments/assets/1be99145-d5d1-4470-8f14-c4ad2f6d5407" />

- **IT/IS**: 430 employees (211F, 219M) across 23 divisions.

<img width="914" height="98" alt="Screenshot 2025-09-05 195128" src="https://github.com/user-attachments/assets/cd44ad6a-559e-4ac0-a192-3e71787a80df" />

- **Production**: 2020 employees (1262F, 758M) across 25 divisions.

<img width="906" height="101" alt="Screenshot 2025-09-05 195401" src="https://github.com/user-attachments/assets/fee51151-d480-40eb-bcd8-94afc7b8e6d2" />

- **Sales**: 331 employees (115F, 216M) across 23 divisions. 

<img width="919" height="90" alt="Screenshot 2025-09-05 195836" src="https://github.com/user-attachments/assets/d20238ab-cc9a-41e8-aff4-33dc8b446d16" />

- **Software Engineering**: 115 employees (49F, 66M) across 19 divisions.  

<img width="915" height="85" alt="Screenshot 2025-09-05 195855" src="https://github.com/user-attachments/assets/ffa27ed8-584e-4181-a816-5b61e003702e" />

### Employee Status Overview
- **Admin Offices**: 78 Active, 1 Future Start, 1 Voluntarily Terminated

<img width="454" height="142" alt="Screenshot 2025-06-17 001553" src="https://github.com/user-attachments/assets/ad2a4a63-1dcb-40cd-9ad5-8f92e7111592" />
 
- **Executive Office**: 24 Active

<img width="451" height="141" alt="Screenshot 2025-06-17 002240" src="https://github.com/user-attachments/assets/04cd7f97-0f2c-4554-b048-9687768af807" />

- **IT/IS**: 375 Active, 31 Terminated for Cause, 17 Leave of Absence, 4 Future Start, 3 Others  

<img width="456" height="187" alt="Screenshot 2025-06-17 004800" src="https://github.com/user-attachments/assets/7f7e29c0-d87a-478b-a07f-7830469642ef" />

- **Production**: 1588 Active, 35 Terminated for Cause, 69 Leave of Absence, 41 Future Start, 287 Voluntarily Terminated  

<img width="444" height="173" alt="Screenshot 2025-06-17 010120" src="https://github.com/user-attachments/assets/568b0d83-3d2e-453b-aa6e-6e6f4522074c" />

- **Sales**: 301 Active, 20 Future Start, 10 Voluntarily Terminated  

<img width="434" height="175" alt="Screenshot 2025-06-17 010847" src="https://github.com/user-attachments/assets/13f748b2-e6c6-464e-8f15-65028f4c5ba9" />

- **Software Engineering**: 92 Active, 20 Voluntarily Terminated, 3 Future Start  

<img width="445" height="178" alt="Screenshot 2025-06-17 011708" src="https://github.com/user-attachments/assets/32f47e85-27be-477d-977f-ad2bf3ebb059" />

### Departmental Pay Zone Distribution
- **Admin Offices**: 42.5% A, 30% B, 27.5% C  

<img width="330" height="223" alt="Screenshot 2025-06-17 015236" src="https://github.com/user-attachments/assets/38774221-5698-49ca-9c82-7e7f0f3fd2d5" />

- **Executive Office**: 37.5% A, 33.33% B, 29.17% C  

<img width="319" height="230" alt="Screenshot 2025-06-17 015614" src="https://github.com/user-attachments/assets/95f72831-dc83-4214-8f6c-e0b8442b0a2a" />

- **IT/IS**: 36.05% A, 32.09% B, 31.86% C  

<img width="321" height="235" alt="Screenshot 2025-06-17 020551" src="https://github.com/user-attachments/assets/2c38569e-f81d-466a-85fe-e2692876b322" />

- **Production**: 35% A, 33.51% B, 31.49% C  

<img width="328" height="233" alt="Screenshot 2025-06-17 020858" src="https://github.com/user-attachments/assets/3bdc8b91-cb82-44c4-9605-cac33b54b509" />

- **Sales**: 36.25% A, 30.82% B, 32.93% C

<img width="329" height="236" alt="Screenshot 2025-06-17 021848" src="https://github.com/user-attachments/assets/708432a7-206d-4212-bf1a-d552e4ab2306" />

- **Software Engineering**: 32.17% A, 31.3% B, 36.52% C

   <img width="327" height="237" alt="Screenshot 2025-06-17 022557" src="https://github.com/user-attachments/assets/16f8294e-c549-4d95-b548-f66c6ab41bf9" />

### Departmental Marital Status Distribution
- **Admin Offices**: 25 Divorced, 22 Single, 18 Widowed, 15 Married

  <img width="397" height="238" alt="Screenshot 2025-06-17 025131" src="https://github.com/user-attachments/assets/52487214-5994-429e-a9a8-62388a017d38" />

- **Executive Office**: 15 Single, 6 Divorced, 2 Widowed, 1 Married

   <img width="388" height="222" alt="Screenshot 2025-06-17 025627" src="https://github.com/user-attachments/assets/f4d6ced7-134d-4656-aa3b-039ecc918be9" />

- **IT/IS**: 119 Widowed, 114 Single, 104 Married, 93 Divorced

<img width="379" height="220" alt="Screenshot 2025-06-17 030302" src="https://github.com/user-attachments/assets/057604d5-231b-4002-b1ec-b86761ec5ebf" />
    
- **Production**: 534 Married, 514 Divorced, 505 Single, 467 Widowed

   <img width="401" height="226" alt="Screenshot 2025-06-17 030958" src="https://github.com/user-attachments/assets/15710683-1d84-48b4-83cc-f499bef983eb" />

- **Sales**: 85 Married, 85 Single, 85 Widowed, 76 Divorced

  <img width="384" height="221" alt="Screenshot 2025-06-17 031654" src="https://github.com/user-attachments/assets/186ca178-584b-4f35-a2ea-821805f366ef" />

- **Software Engineering**: 32 Widowed, 31 Single, 27 Divorced, 25 Married
    
<img width="383" height="230" alt="Screenshot 2025-06-17 032132" src="https://github.com/user-attachments/assets/7f395e91-934c-419b-aecf-c392520d9f23" />

### Departmental Race Distribution
- **Admin Offices**: 25 Black, 24 White, 11 Hispanic, 10 Asian, 10 Other

<img width="420" height="193" alt="Screenshot 2025-06-17 034234" src="https://github.com/user-attachments/assets/c93aa028-95c6-477c-b324-5774da1e570d" />

- **Executive Office**: 8 Other, 5 Asian, 5 Hispanic, 4 Black, 2 White

  <img width="421" height="196" alt="Screenshot 2025-06-17 035002" src="https://github.com/user-attachments/assets/f1cc8ae7-2777-44b0-884c-f9f119e1bf5b" />

- **IT/IS**: 91 Hispanic, 90 Other, 89 Black, 83 White, 77 Asian

   <img width="417" height="188" alt="Screenshot 2025-06-17 035703" src="https://github.com/user-attachments/assets/1477f51c-90d9-4afc-850b-c57db4b47296" />

- **Production**: 430 Asian, 413 White, 400 Black, 390 Other, 387 Hispanic

   <img width="421" height="209" alt="Screenshot 2025-06-17 040632" src="https://github.com/user-attachments/assets/d070cd6f-940e-4376-884c-48e66d6c6076" />

- **Sales**: 82 Asian, 71 Black, 67 Other, 58 Hispanic, 53 White

  <img width="432" height="210" alt="Screenshot 2025-06-17 041050" src="https://github.com/user-attachments/assets/238e49f7-8330-49e6-bba8-93069377ae94" />

- **Software Engineering**: 30 White, 29 Black, 20 Hispanic, 19 Asian, 17 Other  

<img width="421" height="195" alt="Screenshot 2025-06-17 042014" src="https://github.com/user-attachments/assets/e12b5353-3f94-4f41-8a5d-aad300366a8f" />

### Departmental Performance Score
- **Admin Offices**: 58 Fully Meets, 17 Exceeds, 5 PIP

  <img width="557" height="184" alt="Screenshot 2025-06-17 044638" src="https://github.com/user-attachments/assets/50024315-fa03-4899-b9fc-cda0f719ddb2" />

- **Executive Office**: 17 Fully Meets, 1 Exceeds, 1 Needs Improvement, 5 PIP  

<img width="556" height="175" alt="Screenshot 2025-06-17 045228" src="https://github.com/user-attachments/assets/ae5078ba-fc04-4f4e-a645-dd4ce72b7cc9" />

- **IT/IS**: 351 Fully Meets, 38 Exceeds, 21 Needs Improvement, 20 PIP

- <img width="558" height="178" alt="Screenshot 2025-06-17 050751" src="https://github.com/user-attachments/assets/eb7416da-2f61-4433-b4a1-9bf2401f6cbb" />

- **Production**: 1521 Fully Meets, 295 Exceeds, 141 Needs Improvement, 63 PIP

-   <img width="564" height="174" alt="Screenshot 2025-06-17 051538" src="https://github.com/user-attachments/assets/f0a847a0-597f-43b7-a3fa-d8c95e6e0bc7" />

- **Sales**: 299 Fully Meets, 18 Exceeds, 14 Needs Improvement

-  <img width="562" height="183" alt="Screenshot 2025-06-17 052054" src="https://github.com/user-attachments/assets/af9a449d-e895-4de8-8228-c3d730277daf" />

- **Software Engineering**: 115 Fully Meets (100%)

- <img width="542" height="169" alt="Screenshot 2025-06-17 052836" src="https://github.com/user-attachments/assets/3102fc5b-46d1-49b4-b37c-28a5106c2103" />


---

## Key Insights
- **Workforce Size**: Production has the largest workforce (2020 employees), while Executive Office has the smallest (24 employees).  
- **Turnover**: Production has the highest voluntary turnover (287 employees).  
- **Pay Zone Equity**: Admin has the highest % in Pay Zone A, while Software Engineering has the lowest.  
- **Race Distribution**: Production department leads in number of Asian (430) and White (413) employees.  
- **Performance**: Production has notable underperformance (141 “Needs Improvement” + 63 “PIP”). Executive Office shows possible resourcing issues.  

---

## Strategic Recommendations
1. **Monitor Gender Balance** – Ensure fairness and inclusion; investigate if gender disparities contribute to turnover.  
2. **Optimize Departmental Effectiveness** – Review Production scalability and workload distribution.  
3. **Investigate High Turnover** – Conduct exit interviews and strengthen engagement programs in Production.  
4. **Review Pay Structure** – Ensure pay equity across departments and evaluate Admin’s high Pay Zone A distribution.  
5. **Tailor Benefits** – Offer life-stage benefits (e.g., flexible schedules, family support).  
6. **Address Underperformance** – Provide targeted training and workload reviews in Production; clarify roles and resourcing in Executive Office.  

---

## Conclusion
The analysis reveals significant workforce disparities across departments in size, gender, pay zones, and performance.  
Key concerns include high turnover and underperformance in the Production department, and potential resourcing issues in the Executive Office.  
Strategic actions should focus on **equity, engagement, and tailored support**.  
Addressing these areas can improve retention, performance, and departmental balance.  

---

## DASHBOARD

<img width="1340" height="748" alt="Screenshot 2025-09-05 214934" src="https://github.com/user-attachments/assets/4ad8abed-d481-456e-a6c6-aec037025bf1" />
