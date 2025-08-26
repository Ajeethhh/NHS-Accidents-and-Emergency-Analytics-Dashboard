# NHS-Accidents-and-Emergency-Analytics-Dashboard

> **Key Finding (Jan 2025):**  
> The NHS **four-hour target** requires **95%** of A&E patients to be admitted, transferred, or discharged within 4 hours of arrival.  
> However, recent performance has **fallen significantly short**, with an **interim target of only 69.1% achieved**.  
> This serves as a critical indicator of overall NHS performance.  

---

## Project Overview  
This project analyzes **NHS Accident & Emergency (A&E) attendance data** and provides an interactive **Power BI dashboard** to monitor emergency service performance across different regions, departments, and time periods.  

The dashboard helps track:  
- Total A&E attendances  
- % of patients seen within 4 hours  
- Emergency admissions  
- Regional and departmental breakdowns  
- Yearly patient trends and waiting times  

---

## 🗂 Dataset  
The dataset contains records of **A&E attendances** across NHS England regions and providers.  

### Columns included:  
- **All A&E** – type of attendance (e.g., A&E attendances)  
- **A&E Dept** – department type (Major A&E, Minor A&E, Single Specialty, etc.)  
- **Date** – reporting period  
- **NHS Region** – geographical region (e.g., East of England, London)  
- **NHS Provider** – specific hospital/trust  
- **Value** – number of attendances  

Example (first 5 records) after cleaning transposing and unpivoting:  

| All A&E           | A&E Dept                        | Date       | NHS Region                  | NHS Provider                                     | Value  |  
|-------------------|---------------------------------|------------|-----------------------------|-------------------------------------------------|--------|  
| A&E attendances   | Type 1 Departments - Major A&E  | 01-04-2024 | NHS England East Of England | Bedfordshire Hospitals NHS Foundation Trust      | 15343  |  
| A&E attendances   | Type 1 Departments - Major A&E  | 01-04-2024 | NHS England East Of England | Cambridge University Hospitals NHS Foundation    | 10689  |  
| A&E attendances   | Type 1 Departments - Major A&E  | 01-04-2024 | NHS England East Of England | East And North Hertfordshire NHS Trust           | 8892   |  
| A&E attendances   | Type 1 Departments - Major A&E  | 01-04-2024 | NHS England East Of England | East Suffolk And North Essex NHS Foundation Trust| 15078  |  
| A&E attendances   | Type 1 Departments - Major A&E  | 01-04-2024 | NHS England East Of England | Hertfordshire Community NHS Trust                | 0      |  

---

## 📈 Dashboard Features  

### KPI Cards  
- **Total A&E attendances:** 103.2M  
- **% attended < 4 hrs:** 69.1%  
- **% attended > 4 hrs:** 24.7%  
- **Emergency admissions:** 26.8M  

### Visuals & Trends  
- Yearly trend of total A&E attendances (2021–2025)  
- Regional comparisons of attendance numbers  
- Attendances by department (Major, Minor, Specialty)  
- Waiting times analysis (<4 hrs vs. >4 hrs)  
- Patients waiting <4 yrs vs >4 yrs (2021–2025)  

### Filters  
- Year  
- Month  
- NHS Region  

---

## 🛠 Tools & Technologies  
- **Power BI** → Dashboard visualization  
- **Excel / CSV** → Data source  
- **DAX & Power Query** → Data transformation and measures  
