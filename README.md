# business_problem-optimization-_with-pulp-and-linear-programming-
# 🚛 Supply Chain Optimization Model

*Internship Task 4 – Business Problem Optimization using Linear Programming and PuLP*

## 📌 Problem Statement

A manufacturing company operates *3 factories* and supplies *4 distribution centers (DCs). Each factory has capacity constraints, and each DC has specific demand requirements. The challenge is to **minimize total transportation costs* while satisfying all operational constraints.

## 🧠 Objective

> 🔽 Minimize: *Total Transportation Cost*

Subject to:

- ✅ Factory supply limits  
- ✅ Distribution center demand fulfillment  
- ✅ Non-negativity of shipments

This is a classic *Transportation Problem, modeled with **Linear Programming* using the *PuLP* Python library.

---

## 📊 Features

### 🏗 Problem Setup
- Defined *factories, **distribution centers*, supply, demand, and cost matrix
- Verified supply-demand balance

### 🧮 Optimization Model
- *Decision variables*: units shipped from each factory to each DC
- *Objective*: minimize the total cost across all routes
- *Constraints*: supply ≤ capacity, demand ≥ requirement

### ✅ Solution Output
- Optimal shipping quantities for each route
- Minimum total transportation cost
- Constraint checks for feasibility

### 📈 Insights & Analytics
- Network efficiency and active route analysis
- Cost variance and standard deviation across shipping paths
- Factory utilization and demand fulfillment stats
- Supplier diversity and risk assessment
- Economic efficiency ratio (actual vs theoretical minimum)
- Operational complexity and market dominance diagnostics
- Scalability projections for growth scenarios

### 🔍 Scenario Planning
- Demand surge analysis (+10% demand)
- Factory disruption resilience
- Transportation cost inflation impact

### 🧭 Strategic Recommendations
- Cost reduction priorities with alternative routing strategies
- Capacity optimization suggestions
- Risk mitigation (reducing supplier dependency)
- Market opportunities for unused capacity
- Performance KPIs and scoring dashboard

---

## 🛠 Technologies & Libraries

| Tool        | Purpose                                |
|-------------|-----------------------------------------|
| PuLP      | Linear programming modeling             |
| Pandas    | Data handling and tabulation            |
| NumPy     | Mathematical operations                 |
| Matplotlib + Seaborn | Visualization and charts         |
| Tabulate  | Console-friendly tables                 |

---

## 🚀 How to Run

1. *Install Dependencies*
```bash
pip install pulp pandas numpy matplotlib seaborn tabulate
