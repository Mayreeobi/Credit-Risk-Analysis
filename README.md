# Credit Risk Analytics Dashboard & Analysis (Tableau)

---

## 📌 Problem statement

Nova Bank provides personal, medical, education and business loans across the USA, UK and Canada. The bank needs to balance **fair lending** with **effective risk management**:

- Approving too many high-risk loans → financial losses.  
- Being too strict → exclusion of potentially creditworthy customers.

**Challenge:** How can Nova Bank identify safe vs risky borrowers, predict loan defaults, and tune lending policies to remain both profitable and fair?

---

## 🎯 Project objectives

- Evaluate the risk distribution across Nova Bank’s loan portfolio.
- Identify key drivers of default (demographics, geography, credit history, loan purpose).
- Provide strategic recommendations for reducing risky exposure.

---

## ❓ Key questions explored

- What proportion of borrowers are risky, moderate, or safe?
- Which borrower attributes (employment, housing, income, credit history) drive risk?
- Do certain loan purposes (education, medical, business, personal, debt consolidation) carry more risk?  
- Does employment type or home ownership affect risk?  
- How do past defaults or longer credit histories influence outcomes?  
- Which geographies are risk hot-spots?  
- What actionable policies can reduce risky lending without excluding creditworthy borrowers?

---

## 📊 Dashboard Pages

### 🔹 Page 1 — **Borrower Risk Profile** (Who looks risky before lending?)  
![Borrower Risk Profile](https://github.com/Mayreeobi/Credit-Risk-Analysis/blob/main/_Risk%20Profile.png)
*Borrower segmentation by risk score, defaults, employment, and housing.*  

### 🔹 Page 2 — **Loan Performance** (What happened with current loans?)  
![Loan Performance](https://github.com/Mayreeobi/Credit-Risk-Analysis/blob/main/Loan%20Performance.png)
*Analysis of loan balances, defaults, loan purposes, and repayment trends.*  

### 🔹 Page 3 — **Borrower Details** (Drill-down)  
![Borrower Details](https://github.com/Mayreeobi/Credit-Risk-Analysis/blob/main/Details.png)
*Granular view by age, status, grade, loan purpose, and loan amount.*  

---

## 🔎 Key Findings  

**Portfolio Overview**  
- Total borrowers: **32.58K** with **$312.43M** in loans issued.  
- **Default rate**: 21.82% (≈ $77.13M defaulted).  
- **25.54%** of borrowers classified as risky.  
- **Average Risk Score**: 3.51.  
- **17.63%** have past defaults.  

**Risk Distribution**  
- Safe: **15.28%** | Moderate: **59.18%** | Risky: **25.54%**.  
- Borrowers with past defaults are **2.3× more likely** to default again (39% vs 17%).  

**Employment & Housing Patterns**  
- **Unemployed & self-employed** → highest default (22.67% & 22.49%).  
- **Renters** default more than homeowners.  
- "Other" housing category = extremely high defaults (33–42%).  

**Demographic Insights**  
- Age **20–24 yrs** highest risk (28%).  
- **Singles** more risky (26% riskiness).  
- **High school graduates** most vulnerable; **PhD/Master’s** safest.  

**Credit History**  
- Borrowers with **2–5 years** credit history = riskiest group (27.6%).  
- Past defaults significantly increase future risk.  

**Loan Performance**  
- Defaulted loans = **24.7% by value**.  
- Defaults linked to higher interest rates (**13.06% vs 10.44%**) and higher DTI (**42.4%**).  
- **Medical & education loans** most default-prone.  
- **Shorter-term, higher-grade loans** (A/B) are safer.  

---

## ✅ Recommendations  

**1. Strengthen Risk Controls**  
- Reject/flag applicants with **DTI > 60%, LTI > 0.5, credit history < 3 yrs, or multiple past defaults**.  
- Require **co-signers** or **collateral** for borderline applicants.  

**2. Optimize Loan Products**  
- Promote **shorter-term, high-grade loans** (≤ 36 months, Grades A–B).  
- Apply **stricter vetting** for medical & education loans.  
- Introduce **tiered interest rates** for debt-consolidation loans.  

**3. Target Borrower Segments**  
- **Risky**: Small loans, collateral, or deny.  
- **Moderate**: Monitor closely, adjust rates.  
- **Safe**: Reward with loyalty incentives.  

**4. Employment & Housing Focus**  
- Additional checks for **unemployed/self-employed renters**.  
- Incentivize **mortgage/homeowner borrowers** (lower default risk).  
- Special safeguards for **young borrowers (20–24 yrs)**.  

**5. Regional Strategy**  
- Stricter policies in **USA (esp. New York, California)** and **Canada (Ontario, Quebec)**.  
- Regularly track defaults regionally to guide policy.  

**6. Early Monitoring**  
- Track past defaulters separately.  
- Build **early-warning system** for income/job changes.  
- Launch **financial literacy programs** for high-risk groups.  

---

**Impact**: With these recommendations, Nova Bank can cut defaults, reduce losses, and build **profitable yet inclusive lending policies**.  

---

## 📍 Tableau Public 
👉 [Tableau Public](https://public.tableau.com/app/profile/chinyere.obi8867/viz/Creditriskanalysis_17575058985000/RiskProfile)

---

## 🛠️ Skills Demonstrated
- Data storytelling & dashboard design (Tableau)  
- Segmentation analysis (Safe / Moderate / Risky)  
- Business recommendations for financial institutions  

---

## 📂 Deliverables
- Tableau dashboard (packaged workbook)  
- Executive summary report (PDF)  
- GitHub README with findings & recommendations  

---

## 📌 About #dataDNA Challenge
The **#dataDNA Challenge** by Onyx Data provides real-world datasets for data visualization and storytelling. This project was created as part of the September 2025 challenge on **Credit Risk Analysis**.  

⚡ This project simulates the role of a Credit Risk Analyst, helping banks spot risky borrowers, protect against defaults, and still keep lending fair.

---

