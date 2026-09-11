# Healthcare Operations: Data Analytics Practice

## 📌 Practice Module Overview
This module is part of an ongoing Data Analytics practice regimen (`eksel-praktis`). Working with synthetic, intentionally "dirty" healthcare data, the goal of this exercise was to build muscle memory in **Microsoft Excel** by executing a full data cleaning pipeline and building an interactive Dashboard for Executive Stakeholders.

## 🛠️ Skills Mastered in this Module
- **Data Engineering (Excel):** Cleaned invisible spaces (`TRIM`), handled missing values/blanks using Logic Gates (`IF`, `ISBLANK`), and consolidated fragmented patient records.
- **Data Modeling:** Extracted chronological data (Months) from raw timestamps to build admission funnels.
- **Data Visualization:** Built dynamic Pivot Tables and connected Slicers to create an interactive, presentation-ready Dashboard.

---

## 📊 Key Findings

### 1. Department Financials & Revenue Contribution
Cardiology, Neurology, Oncology, and Pediatrics drive the core financial volume. Aggregate patient costs scale evenly across departments after successfully filtering out unassigned/dirty records ("Unknown" buckets).

### 2. Admission Funnels & Volume Trends
Patient intake exhibits a stable chronological baseline throughout most of the year. However, there is a **sharp upward volume surge** arriving toward the final months of the calendar year.

### 3. Bed Efficiency & Length of Stay
The average length of stay remains remarkably consistent across all clinical departments, hovering tightly between **15 and 16 days**. This signals uniform operational pacing regardless of the medical specialty.

### 4. Billing Outliers & Revenue Concentration
High-cost anomalies are led by peak individual bills (e.g., Michael Johnson at **$56,390.68**), demonstrating that high-tier inpatient costs are driven by specific acute cases rather than sweeping departmental inflation.

---

## 🎯 Strategic Recommendations (Simulated)

1. **Implement Upfront Data Capture Validation:** 
   Mandate required fields for patient names at initial intake to eliminate the multi-million dollar "Unknown" data aggregation bucket at the data entry layer.
2. **Investigate Year-End Volume Spikes:** 
   Allocate nursing and administrative staff proactively ahead of the final-quarter admission surge to prevent physician burnout and maintain bed turnover efficiency.
3. **Audit Long-Stay Patient Protocols:** 
   Review clinical pathways for treatments exceeding the 15-day length-of-stay average to identify potential bottlenecks in discharge planning.
4. **Monitor Acute-Care Cost Drivers:** 
   Establish a specialized financial review tier for single-patient treatments crossing the $50,000 threshold to optimize insurance reimbursement and resource allocation.
