# Insurance Risk & Claims Analysis – Power BI Dashboard

An interactive Power BI dashboard built for an insurance company to analyze its policyholder base and claim patterns, enabling data-driven business decisions. The dashboard centralizes policy and claims data that was previously scattered across multiple sources, giving stakeholders a clear view of performance and trends.

## KPIs Tracked
- **Total Policies** – measures the size of the active customer base
- **Total Claim Amount** – tracks the overall financial impact of claims
- **Claim Frequency** – analyzes how often claims are made
- **Average Claim Amount** – assesses claim severity and risk exposure
- **Gender-wise Total Policies** – customer distribution across genders for segmentation

## Charts & Visuals
All visuals are built around two dynamic measures — **Total Claim Amount** and **Total Policies** — to compare, filter, and segment the data:

- By Car Use (Donut Chart) – policy distribution and claims by usage type (personal, commercial)
- By Car Make (Bar Chart) – brand-based risk comparison
- By Coverage Zone (Donut Chart) – regional risk analysis
- By Age Group (Histogram) – claim trends across age brackets
- By Car Year (Area Chart) – impact of vehicle age on policies and claims
- By Kids Driving (Ribbon Chart) – effect of young drivers in a household
- By Education (Pie Chart) – education level vs policy adoption/claims
- By Education & Marital Status (Matrix Heat Grid) – combined customer profiling

## Dataset
The dataset includes policyholder demographics (age, gender, marital status, education, household income, parental status), vehicle details (make, model, year, color, usage type), coverage zone, and claims data (claim amount, claim frequency). Together, these support risk profiling, customer segmentation, and premium optimization use cases.

## Tools Used
Power BI Desktop

## Files
- `Insurance_Risks_and_Claims_Analysis.pbix` – Power BI project file
- `insurance_policies_data.xlsx` – dataset used for analysis
- `Business_requirements.docx` – business requirements and KPI/chart specifications
- `Domain_Doc.docx` – data dictionary explaining each field in the dataset
