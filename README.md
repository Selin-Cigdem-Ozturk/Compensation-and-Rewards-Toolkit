# Total Rewards Modeling & Compensation Toolkit

This project demonstrates an end-to-end **compensation planning and salary benchmarking model** built for a simulated **250-employee organization in Sweden**. The model combines market benchmarking, salary band architecture, compa-ratio analysis, merit increase logic, and short-term incentive (STI) calculations to simulate a full annual compensation review cycle.

The goal is to show how compensation philosophy can be translated into a structured, data-driven framework that supports fair pay decisions while staying within payroll budgets.

---

## Project Highlights

- **250 employee compensation dataset**
- **Market benchmarking methodology**
- **Salary band structure (G5–G10)**
- **Compa-ratio analysis**
- **Performance-based merit matrix**
- **Short-term incentive (STI) model**
- **Payroll budget control**
- **Department-level compensation summary**
- **Net pay simulation with deductions**

The model connects employee data, salary structures, performance ratings, and budget constraints to generate realistic compensation outcomes.

---
## Objectives

The project is designed to answer the following business questions:

- How should employees be positioned against market benchmarks?
- How can merit increases be differentiated fairly?
- How do performance and pay positioning interact?
- How can salary review decisions stay within budget?
- What is the total payroll impact of proposed increases?
- What does each employee’s final net pay look like after STI and deductions?

---

## What the model includes

### Employee-level compensation dataset
The core dataset contains 250 employee records with fields such as:

- Employee ID
- Name
- Department
- Title
- Recruitment Date
- Performance Manager
- Unit / Location
- Country
- Employment Type
- Job Level
- Job Grade
- Monthly Gross Salary
- Pay Frequency
- Salary Band Min / Mid / Max
- Compa-ratio
- Compa-ratio Group
- Performance Rating
- Salary Increase %
- Salary Increase Amount
- New Gross Salary
- STI %
- Target STI
- Multiplier
- Final STI
- Tax %
- Benefit Plan
- Tax Amount
- Pension
- Health Premium
- Total Deductions
- Net Pay

### Supporting frameworks
The project also includes:

- Market benchmarking methodology
- Salary band structure
- Merit matrix
- STI target table
- Budget control table
- Department summary pivot
- Supporting charts and visuals

---

**Key results**

| Metric | Value |
|------|------|
| Total Payroll | 13,854,899 |
| Proposed Merit Budget | 3% |
| Actual Merit Spend | 2.27% |
| Total Merit Spend | 355,650 |
| Remaining Budget Capacity | 59,996 |

The results show that the salary increases remain within the defined compensation budget.

---

## Department Summary

The project also includes department-level analysis.

| Department | Employees | Budget Increase |
|-----------|-----------|----------------|
| Finance | 42 | 2.32% |
| HR | 35 | 2.80% |
| IT | 51 | 1.93% |
| Marketing | 36 | 2.42% |
| Operations | 46 | 2.75% |
| Sales | 40 | 3.61% |

Total payroll increases from **13.85M to 14.21M**, representing an overall growth of **2.57%**.

---
## Key Formulas

Compa-ratio = Monthly Gross Salary / Mid

Salary Increase Amount = Monthly Gross Salary × Salary Increase %

New Gross Salary = Monthly Gross Salary + Salary Increase Amount

Target STI = New Gross Salary × STI %

Final STI = Target STI × Performance Multiplier

Tax Amount = (New Gross Salary + Final STI) × Tax %

Pension = New Gross Salary × 5%

Total Deductions = Tax Amount + Pension + Health Premium

Net Pay = New Gross Salary + Final STI - Total Deductions













