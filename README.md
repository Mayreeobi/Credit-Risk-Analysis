# Credit Risk Analytics Dashboard & Analysis (Tableau)

---

## 📌 Problem statement

Nova Bank provides personal, medical, education and business loans across the USA, UK and Canada. The bank needs to balance **fair lending** with **effective risk management**:

- Approving too many high-risk loans → financial losses.  
- Being too strict → exclusion of potentially creditworthy customers.

**Challenge:** How can Nova Bank identify safe vs risky borrowers, predict loan defaults, and tune lending policies to remain both profitable and fair?

---

## 🎯 Project objectives

- Identify which groups of borrowers are more likely to default.  
- Explore loan purposes, grades and terms to find higher-risk products.  
- Analyze how Loan-to-Income (LTI) and Debt-to-Income (DTI) ratios affect repayment.  
- Compare borrower profiles by demographics (age band, gender, education, employment, home ownership).  
- Assess the effect of past defaults and credit history length.  
- Spot regional differences (USA vs UK vs Canada).  
- Segment borrowers into **Safe / Moderate / Risky** to support decision making.

---

## ❓ Key questions explored

- Which types of borrowers are more likely to default?  
- Do certain loan purposes (education, medical, business, personal, debt consolidation) carry more risk?  
- How do LTI and DTI relate to repayment outcomes?  
- Does employment type or home ownership affect risk?  
- How do past defaults or longer credit histories influence outcomes?  
- Are there clear differences between borrowers in the USA, UK and Canada?  
- Which loan grades or terms are safer, which are riskier?  
- Can we group borrowers into “Safe” vs “Risky” clusters?

---

## 📊 Dashboard (3 pages)

### 🔹 Page 1 — **Borrower Risk Profile** (Who looks risky before lending?)  
- KPI tiles: Average Risk Score, Borrowers Profiled, % with Past Defaults.  
- Donut: Risk segmentation (Safe / Moderate / Risky).  
- Heatmap: Employment × Home Ownership vs % Risky.  
- Bar chart: Past Defaults impact (Y/N).
  ![Borrower Risk Profile](https://github.com/Mayreeobi/Credit-Risk-Analysis/blob/main/_Risk%20Profile.png)


### 🔹 Page 2 — **Loan Performance** (What happened with current loans?)  
- KPI tiles: Total Loans Issued, Default Rate, Total Default Exposure.  
- Bar chart: % Default by Loan Purpose.  
- Scatter: Loan-to-Income vs Default %.  
- Map: Default rate across USA, UK, Canada.
  ![Loan Performance](https://github.com/Mayreeobi/Credit-Risk-Analysis/blob/main/Loan%20Performance.png)

### 🔹 Page 3 — **Borrower Details** (Drill-down)  
- Interactive table of borrower-level details.  
- Filters for demographics, loan purpose, and grade.
   ![Borrower Details](https://github.com/Mayreeobi/Credit-Risk-Analysis/blob/main/Details.png)


---

## 🔎 Key findings & recommendations

### Key insights
- Past defaults and short credit histories (< 5 years) are strong predictors of risk.  
- Medical and education loans display higher default rates relative to other purposes.  
- Borrowers with **DTI > 60%** or **LTI > 0.5** are markedly riskier.  
- Unemployed borrowers and renters show higher default rates than employed homeowners.  
- Some regional variation exists; the USA shows slightly higher exposure than UK/Canada.  
- Shorter terms and higher loan grades (A, B) tend to be safer.

### Recommendations
1. Tighten lending thresholds for applicants with:  
   - DTI > 60% or LTI > 0.5  
   - Credit history < 3 years  
   - ≥ 2 past delinquencies or prior default on file  
2. Favor shorter terms and higher grades for riskier product segments.  
3. Require additional checks or co-signers for medical/education loans.  
4. Use the **Safe / Moderate / Risky** segmentation to set dynamic approval thresholds.  
5. Monitor regional policy effects and adjust by market as needed.

---

## 💻 Tools Used

- **Tableau** — visualization & dashboard (Tableau Public workbook link).  
- **Excel / CSV** — data prep and sample datasets.  
- **GitHub** → Project documentation & portfolio



## 📂 Repository Structure
```
Nova-Bank-Credit-Risk/
│── data/                 # (Optional: clean dataset, sample provided if allowed)
│── dashboard/            # Tableau workbook (.twbx)
│── images/               # Screenshots for README
│── README.md             # Project documentation

Nova-Bank-Credit-Risk/
├─ data/ # raw and cleaned sample data (if allowed)
├─ dashboard/ # Tableau workbook (.twbx or packaged workbook)
├─ images/ # screenshots used in README
├─ insights.md # short findings & charts export
└─ README.md # this file
```
## 📍 Tableau Public / Demo
👉 [Tableau Public](https://public.tableau.com/app/profile/chinyere.obi8867/viz/Creditriskanalysis_17575058985000/RiskProfile)


⚡ This project simulates the role of a Credit Risk Analyst – helping banks spot risky borrowers, protect against defaults, and still keep lending fair.
