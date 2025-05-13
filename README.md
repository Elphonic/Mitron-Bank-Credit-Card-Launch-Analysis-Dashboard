# Mitron Bank Credit Card Market Analysis & Dashboard

## Project Objective

Mitron Bank, a legacy financial institution, is planning to launch a new credit card to broaden its reach in the financial sector. AtliQ Data Services conducted a pilot study using customer data to analyze the target market, derive key insights, and provide a Power BI dashboard to support strategic decisions.

---

## Problem Statement

Mitron Bank provided a dataset of 4,000 customers across five Indian cities. They aim to identify potential target segments for launching a new credit card product. The goal was to analyze customer behavior, payment preferences, and spending patterns to guide the product design and marketing strategy.

---

## Project Structure

### Phase 1: Data Understanding & Exploration – Jupyter Notebook

**Objective:** Understand the dataset and perform exploratory data analysis to detect trends and gaps.

**Key Libraries Used:**  
`pandas`, `numpy`, `matplotlib`, `seaborn`, `warnings`

**Tasks Performed:**
- Loaded and cleaned the dataset
- Analyzed customer demographics (age, gender, city)
- Examined payment type usage
- Compared total spend vs income
- Identified key customer segments

Folder: `Phase_1_Exploratory_Analysis/`

---

### Phase 2: Business Insights & A/B Testing – Jupyter Notebook

**Objective:** Dive deeper into the 21–24 age group, an untapped segment with high potential.

**Key Libraries Used:**  
`pandas`, `matplotlib`, `seaborn`, `scipy`, `statsmodels`

**Insights Derived:**
- Age group 21–24 forms ~17% of the customer base
- They earn less than ₹50,000 annually and lack credit history
- Credit card usage and average credit spend is relatively low
- They prefer UPI and debit card payments
- Most popular spend categories: **Electronics**, **Entertainment**, **Groceries**, and **Health & Wellness**
- A/B testing validates targeting this group with a custom credit card

Folder: `Phase_2_AB_Testing_Target_Customers/`

---

### Phase 3: Power BI Dashboard – Credit Card Launch Strategy

**Objective:** Build an interactive dashboard for Mitron Bank’s strategy team to visualize insights and make data-driven decisions.

**Tool Used:** Power BI

#### Dashboard Highlights:
- **Overview Page:** Customer trends and total spend behavior
- **Target Segment Page:** Detailed analysis of the 21–24 age group


**Dashboard Link:** [🔗 Click here to view Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMjlmYTc0YWMtNWI2Yy00N2FlLWFhN2QtYjIwY2IxMzNkODYyIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)  

## Key Takeaways

- A strong opportunity exists in the **21–24 age group** to introduce **entry-level credit cards**.
- This group shows **low credit usage** but **high digital payment adoption** – ideal for digital-first products.
- Credit card product positioning should focus on:
  - Building credit history
  - Offering cashback or rewards in **electronics**, **entertainment**, and **grocery** categories
  - Providing low or no annual fee cards with quick approvals

---

## Conclusion

This project demonstrates how data analytics and interactive dashboards can empower financial institutions to make strategic product decisions. Mitron Bank can leverage these insights to tap into a growing customer base and launch a product tailored to the needs of the digital generation.

---

## Tech Stack

- **Python**: Jupyter Notebook
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`, `statsmodels`
- **Visualization**: Power BI
- **Statistical Analysis**: A/B Testing using `statsmodels` and `scipy.stats`
- **Version Control**: GitHub

---
