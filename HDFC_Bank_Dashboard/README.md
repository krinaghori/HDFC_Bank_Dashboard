<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&pause=1000&color=1E5BFF&center=true&vCenter=true&width=700&lines=Filter+%7C+Explore+%7C+Visualize+%7C+Decide;500+Branches+%C2%B7+500K+Transactions+%C2%B7+3+Dashboards;Built+in+Power+BI+%F0%9F%93%8A" alt="Typing SVG" />

<br/>

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-1E5BFF?style=for-the-badge)
![Dataset](https://img.shields.io/badge/Dataset-HDFC_Bank_Banking_Data-E31837?style=for-the-badge)
![Branches](https://img.shields.io/badge/Branches-500-22C55E?style=for-the-badge)
![Transactions](https://img.shields.io/badge/Transactions-500K-0EA5E9?style=for-the-badge)
![Pages](https://img.shields.io/badge/Report_Pages-3-F97316?style=for-the-badge)
![Visuals](https://img.shields.io/badge/Data_Visuals-29-A855F7?style=for-the-badge)
![Slicers](https://img.shields.io/badge/Slicers-7_per_page-EC4899?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-10B981?style=for-the-badge)

<br/>

[![Watch the Presentation](https://img.shields.io/badge/%E2%96%B6_Watch_the_Presentation-EF4444?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1fISE89XsNp_W9FODAEfjrGS7lPT0t_hT/view?usp=drive_link)
[![Dashboard Preview](https://img.shields.io/badge/%F0%9F%96%BC_Dashboard_Preview-1E5BFF?style=for-the-badge)](#-dashboard-preview)
[![Key Insights](https://img.shields.io/badge/%F0%9F%8F%86_Key_Insights-F59E0B?style=for-the-badge)](#-results--insights)
[![How to Open](https://img.shields.io/badge/%E2%96%B6_How_to_Open-10B981?style=for-the-badge)](#-how-to-open--use)

<br/>

> 🚀 A **3-page Power BI report** for **HDFC Bank** that turns **deposit targets, the loan book and 500K transactions across 500 branches** into interactive dashboards — 12 KPI cards, 11 charts, 3 maps, 3 matrices and 7 slicers — so deposits, loans, EMI, NPA, branches and transaction channels can be explored in real time.

</div>

---

## 📑 Table of Contents

1. [Overview](#-overview)
2. [Problem Statement](#-problem-statement)
3. [Features](#-features)
4. [Key Features](#-key-features)
5. [Project Structure](#-project-structure)
6. [Dashboard Layout](#-dashboard-layout)
7. [Data Preparation & Modelling](#-data-preparation--modelling)
8. [Data Model & Fields](#-data-model--fields)
9. [Panel 1 — KPI Cards](#-panel-1--kpi-cards)
10. [Panel 2 — Filters](#-panel-2--filters)
11. [Panel 3 — Deposits vs Target](#-panel-3--deposits-vs-target)
12. [Panel 4 — Loan Portfolio](#-panel-4--loan-portfolio)
13. [Panel 5 — Branch Performance](#-panel-5--branch-performance)
14. [Panel 6 — Transactions](#-panel-6--transactions)
15. [Tech Stack](#-tech-stack)
16. [Results & Insights](#-results--insights)
17. [Advantages](#-advantages)
18. [How to Open & Use](#-how-to-open--use)
19. [Project Presentation](#-project-presentation)
20. [Dashboard Preview](#-dashboard-preview)
21. [License](#-license)
22. [Author](#-author)
23. [Acknowledgements](#-acknowledgements)

---

## 🔭 Overview

**HDFC Bank Dashboard** is a 3-page `.pbix` report built on banking data for **500 branches** — **data as on 30 Apr 2025**. A dark-navy sidebar holds the page navigation (*Deposits vs Target*, *Loan Portfolio*, *Branch Performance*), a row of **7 slicers** and a **Clear Filter** button sit on top of every page, and the main canvas shows **four headline KPI cards** followed by bar, column, line, donut and treemap charts, a map and a drill-down matrix.

Every visual is **live and connected** to one data model — choose a Region, Zone, Branch or Product and the KPI cards, charts and matrices update together. All figures are driven by **DAX measures** stored in a single `Measure Table`.

<div align="center">

| 💰 **₹2K Cr** | 🏦 **₹37,949 Cr** | 🏢 **500** | 🔁 **500K** |
|:---:|:---:|:---:|:---:|
| Total Deposits | Total Loan Book | Total Branches | Total Transactions |

</div>

---

## ❗ Problem Statement

Deposit targets, loan books and transaction logs are usually kept in separate tables and reports, which makes them hard to read as rows and columns. Bank managers need quick answers to questions like:

- 💰 How much have we collected against the deposit target — by month, region, zone, city and branch?
- 📈 How fast are deposits growing compared with the previous year?
- 🏦 Which loan products make up the portfolio, and how healthy is it (NPA %, loan status)?
- 💵 How much EMI is being collected, and is the trend rising or falling?
- 🏢 Which branches and regions lead on deposits, loans and revenue?
- 💳 Which transaction channels do customers use most?

**HDFC Bank Dashboard** answers all of these across **three interactive pages**.

---

## ✨ Features

| Feature | Visual | Description |
|---|---|---|
| 💰 **Total Deposits** | Card | Total deposits for the current filter, with previous year and % change |
| 🎯 **Deposit Target** | Card | Annual deposit target, with previous year and % change |
| 📊 **Achievement %** | Card | Actual deposits as a % of target |
| 📈 **YoY Deposit Growth %** | Card | Year-over-year growth in deposits |
| 🏦 **Total Loan Book** | Card | Total loans outstanding in the book |
| 👥 **Active Loans** | Card | Number of active loan accounts |
| 💵 **EMI Collection** | Card | EMI collected, with previous year and % change |
| ⚠️ **NPA %** | Card | Non-performing assets as a % of the book |
| 📍 **Total Branches** | Card | Branch count, with previous year |
| 🔁 **Total Transactions** | Card | Transaction count, with previous year |
| 🏧 **Avg Transactions per Branch** | Card | Transactions divided by branches |
| 🏆 **Best Branch** | Text Card | Top-performing branch by target achievement |
| 🎛️ **Filters** | 7 Slicers + Clear Filter | Financial Year, Quarter, MonthName, Region, Zone, BranchName, ProductName |
| 📊 **Actual Deposits vs Target** | Clustered Column Chart | Monthly actual vs target |
| 📈 **Deposit Trend** | Line Chart | Drill down Year → Quarter → Month |
| 🍩 **Deposits by Product Type** | Donut Chart | Product mix of deposits |
| 🗺️ **Geographic Distribution** | Map (3 pages) | Deposits, loan exposure and branch performance by city |
| 🌳 **Loan Portfolio by Product** | Treemap | Loan book per product |
| 📉 **Outstanding by Product** | Clustered Bar Chart | Outstanding loan amount per product |
| 💵 **EMI Collection Trend** | Line Chart | Drill down Year → Quarter → Month |
| 🚦 **Loan Status** | Donut Chart | Current / Delayed / NPA / Closed |
| 💎 **Revenue by Branch Hierarchy** | Clustered Bar Chart | Drill down Region → Zone → City → Branch |
| 🔁 **Transactions Trend** | Line Chart | Drill down Year → Quarter → Month → Day |
| 💳 **Transaction Type Distribution** | Donut Chart | EMI, ATM, RTGS, NEFT, Withdrawal, UPI, Deposit |
| 🏢 **Branch Type Performance** | Clustered Column Chart | Actual deposits vs total loan book by branch |
| 🧮 **Matrices (3)** | Pivot Tables | Branch hierarchy, loan portfolio and branch scorecard with drill-down |

---

## 🌟 Key Features

| Feature | Description |
|---|---|
| 🔗 **One Connected Model** | All visuals read from one star-style model, so filters apply consistently across pages |
| 🧮 **DAX Measures** | Achievement %, variance, YoY growth, NPA %, EMI collection and more live in one `Measure Table` |
| 🧭 **Drill-down Hierarchies** | Region → Zone → City → Branch and Year → Quarter → Month (→ Day) |
| 🎛️ **Same Filters on Every Page** | 7 slicers plus a **Clear Filter** button on all three pages |
| 🗺️ **Map Views** | Deposits, loan exposure and branch performance plotted by city |
| 🎨 **Branded Design** | HDFC-style navy and red theme, icon-based KPI cards and a faint building watermark |
| 🧭 **Sidebar Navigation** | Buttons switch between *Deposits vs Target*, *Loan Portfolio* and *Branch Performance* |
| 🖼️ **Fit-to-Page Canvas** | Designed at 1920 × 1080 so it scales across screen sizes |
| ♻️ **Native Visuals Only** | Card, Column, Bar, Line, Donut, Treemap, Map and Matrix |

---

## 📁 Project Structure

```
📦 HDFC-Bank-Dashboard/
 ┣ 📄 README.md                                      ← Project documentation (you're here!)
 ┣ 📊 HDFC_Bank_Dashboard.pbix                       ← Power BI report (3 pages)
 ┣ 🖼️ Page_1_-_Deposits_vs_Target_Dashboard.png      ← Page 1 screenshot
 ┣ 🖼️ Page_2_-_Loan_portfolio_Breakdown.png          ← Page 2 screenshot
 ┣ 🖼️ Page_3_-_Branch_Performance_dashboard.png      ← Page 3 screenshot
 ┗ 📁 assets/
    ┗ 🎞️ video_thumbnail.png                         ← Clickable presentation thumbnail
```

> 🎬 The **project presentation** is hosted on **Google Drive** — [watch it here](https://drive.google.com/file/d/1fISE89XsNp_W9FODAEfjrGS7lPT0t_hT/view?usp=drive_link).

---

## 🖥️ Dashboard Layout

Every page shares the same frame: **sidebar navigation on the left, 7 slicers on top, 4 KPI cards, then charts and a matrix.**

```
┌──────────────────┬───────────────────────────────────────────────────────────┐
│  HDFC BANK       │ Financial Year │ Quarter │ Month │ Region │ Zone │ Branch │ Product │ Clear │
│                  │┌───────────────┬───────────────┬───────────────┬──────────┐│
│ > Deposits vs    ││ Total Deposits│ Deposit Target│ Achievement % │ YoY Growth││
│   Target         │└───────────────┴───────────────┴───────────────┴──────────┘│
│                  │┌───────────────┬───────────────┬───────────────┬──────────┐│
│   Loan Portfolio ││ Actual vs     │ Deposit Trend │ Deposits by   │ Geographic││
│                  ││ Target (col)  │ (line, drill) │ Product(donut)│ Map       ││
│   Branch         │└───────────────┴───────────────┴───────────────┴──────────┘│
│   Performance    │┌───────────────────────────────────────────────┬──────────┐│
│                  ││ Deposit Performance by Branch Hierarchy       │ Key      ││
│                  ││ (matrix: Region > Zone > City > Branch)       │ Insights ││
│                  │└───────────────────────────────────────────────┴──────────┘│
└──────────────────┴───────────────────────────────────────────────────────────┘
                              📄 Page 1 — Deposits vs Target
```

```
┌──────────────────┬───────────────────────────────────────────────────────────┐
│  HDFC BANK       │ 7 slicers + Clear Filter                                  │
│                  │┌───────────────┬───────────────┬───────────────┬──────────┐│
│   Deposits vs    ││ Total Loan    │ Active Loans  │ EMI Collection│ NPA %    ││
│   Target         ││ Book          │               │               │          ││
│                  │└───────────────┴───────────────┴───────────────┴──────────┘│
│ > Loan Portfolio │┌───────────────┬───────────────┬───────────────────────────┐│
│                  ││ Loan Portfolio│ Outstanding by│ EMI Collection Trend      ││
│   Branch         ││ by Product    │ Product (bar) │ (line, drill)             ││
│   Performance    ││ (treemap)     │               │                           ││
│                  │└───────────────┴───────────────┴───────────────────────────┘│
│                  │┌───────────────┬───────────────┬───────────────────────────┐│
│                  ││ Loan Exposure │ Loan Status   │ Loan Portfolio Matrix     ││
│                  ││ (map)         │ (donut)       │ (Region > Zone > Branch)  ││
│                  │└───────────────┴───────────────┴───────────────────────────┘│
└──────────────────┴───────────────────────────────────────────────────────────┘
                              📄 Page 2 — Loan Portfolio Breakdown
```

```
┌──────────────────┬───────────────────────────────────────────────────────────┐
│  HDFC BANK       │ 7 slicers + Clear Filter                                  │
│                  │┌───────────────┬───────────────┬───────────────┬──────────┐│
│   Deposits vs    ││ Total Branches│ Total Trans.  │ Avg Trans. /  │ Best     ││
│   Target         ││               │               │ Branch        │ Branch   ││
│                  │└───────────────┴───────────────┴───────────────┴──────────┘│
│   Loan Portfolio │┌───────────────┬───────────────────────┬───────────────────┐│
│                  ││ Branch Network│ Revenue by Hierarchy  │ Transactions Trend││
│ > Branch         ││ (map)         │ (bar, drill)          │ (line, drill)     ││
│   Performance    │├───────────────┼───────────────────────┼───────────────────┤│
│                  ││ Transaction   │ Branch Type           │                   ││
│                  ││ Types (donut) │ Performance (column)  │                   ││
│                  │└───────────────┴───────────────────────┴───────────────────┘│
│                  │ Branch Performance Scorecard (matrix) + Key Insights        │
└──────────────────┴───────────────────────────────────────────────────────────┘
                              📄 Page 3 — Branch Performance
```

---

## 🧪 Data Preparation & Modelling

The report is built on a **star-style model** of dimension, fact and target tables, with every calculation stored as a DAX measure.

| # | Step | What it does |
|:---:|---|---|
| 1️⃣ | **Load source tables** | Branch, product, deposit-target, loan-status and transaction data are loaded into Power BI |
| 2️⃣ | **Build dimensions** | `DimBranch` (Branch, City, Zone, Region), `DimDate` and `DimProduct` |
| 3️⃣ | **Build fact / target tables** | `FactTransactions`, `BranchDepositTargets` and `LoanStatusData` |
| 4️⃣ | **Create relationships** | Dimensions are linked to the fact and target tables so slicers filter every page |
| 5️⃣ | **Add date hierarchy** | `Year` → `Quarter` → `Month` (→ Day) drilldown for the trend charts |
| 6️⃣ | **Create `Measure Table`** | One table that holds all DAX measures (deposits, loans, EMI, NPA, transactions) |
| 7️⃣ | **Define branch hierarchy** | Region → Zone → City → Branch for the matrices and bar chart |
| 8️⃣ | **Design the pages** | Navy sidebar, icons, KPI cards, slicers and a Clear Filter button on each page |

---

## 📋 Data Model & Fields

**📌 Dashboard at a glance**

| Metric | Value |
|---|---|
| 📄 Report pages | **3** |
| 📊 Data visuals | **29** (12 cards, 11 charts, 3 maps, 3 matrices) |
| 🎛️ Slicers per page | **7** + Clear Filter button |
| 🏢 Branches | **500** |
| 🔁 Transactions | **500K** |
| 📆 Data as on | **30 Apr 2025** |
| 🗺️ Regions | Central · East · North · South · West |

**📌 Tables in the model**

| Table | Role |
|---|---|
| 🏢 `DimBranch` | Branch, City, Zone, Region |
| 📅 `DimDate` | Year, Quarter, Month, MonthName, Financial Year |
| 🛍️ `DimProduct` | ProductName |
| 🎯 `BranchDepositTargets` | Deposit targets by branch and product |
| 🚦 `LoanStatusData` | Loan `Status` and `Amount_Cr` |
| 🔁 `FactTransactions` | Transactions with `TransactionType` |
| 🧮 `Measure Table` | All DAX measures |

**📌 Fields and measures used on the dashboard**

| Field / Measure | Used In |
|---|---|
| `Total Deposits` · `Actual Deposits` | Total Deposits card · Actual vs Target · Deposit Trend · Maps · Matrices |
| `Deposit Target` | Deposit Target card · Actual vs Target · Branch hierarchy matrix |
| `Achievement %` · `Achievement Gap %` · `Variance (₹ Cr)` | Achievement card · Branch hierarchy matrix · Scorecard |
| `YoY Deposit Growth %` | YoY card · Branch hierarchy matrix |
| `Total Loan Book` · `Loan Book PY` | Loan Book card · Treemap · Loan matrix · Branch Type chart |
| `Active Loans` · `Outstanding` | Active Loans card · Outstanding by Product · Loan matrix |
| `EMI Collection` · `NPA %` | EMI & NPA cards · EMI trend · Loan matrix · Loan map |
| `Total Branches` · `Total Transactions` · `Avg Transactions Per Branch` | Branch cards · Transactions Trend · Transaction Type donut · Scorecard |
| `ProductName` · `TransactionType` · `Status` | Treemap & bars · Transaction donut · Loan Status donut |
| `Region` · `Zone` · `City` · `BranchName` | Slicers · Maps · Matrices · Bar charts |
| `Year` · `Quarter` · `Month` · `MonthName` · `Financial Year` | Slicers · Trend charts |

---

## 💰 Panel 1 — KPI Cards

> **Twelve native Card visuals** — four on each page, each with a previous-year comparison and a % change.

| Page | Card | Measure | Shown on dashboard | Previous year | Change |
|---|---|---|---|---|---|
| 🟥 Deposits | 💰 Total Deposits | `Total Deposits` | **₹2K Cr** | ₹1.8K Cr | 🟢 +14.18% |
| 🟥 Deposits | 🎯 Deposit Target | `Deposit Target` | **₹49K Cr** | ₹48.9K Cr | 🟢 +18.33% |
| 🟥 Deposits | 📊 Achievement % | `Achievement %` | **3.60%** vs target | — | 🟢 +9.4% |
| 🟥 Deposits | 📈 YoY Deposit Growth % | `YoY Deposit Growth %` | **49.85%** | 48.00% | 🟢 +1.6% |
| 🟦 Loans | 🏦 Total Loan Book | `Total Loan Book` | **₹37,949 Cr** | ₹35,000 Cr | 🟢 +14.51% |
| 🟦 Loans | 👥 Active Loans | `Active Loans` | **77,775** | 75,000 | 🟢 +11.61% |
| 🟦 Loans | 💵 EMI Collection | `EMI Collection` | **₹383 Cr** | ₹375 Cr | 🟢 +14.97% |
| 🟦 Loans | ⚠️ NPA % | `NPA %` | **2.10%** | 2.56% | 🟢 −0.46% (improved) |
| 🟩 Branches | 📍 Total Branches | `Total Branches` | **500** | 480 | 🟢 +4.17% |
| 🟩 Branches | 🔁 Total Transactions | `Total Transactions` | **500K** | 489K | 🟢 +14.29% |
| 🟩 Branches | 🏧 Avg Transactions / Branch | `Avg Transactions Per Branch` | **1.00K** | 0.7K | 🟢 +112.52% |
| 🟩 Branches | 🏆 Best Branch | Text card | **Connaught Place Branch** — New Delhi Zone | — | — |

> [!TIP]
> ✅ **Reading it:** every comparison arrow is green — deposits are up **14.18%**, the loan book is up **14.51%**, transactions are up **14.29%**, and **NPA fell from 2.56% to 2.10%**.

---

## 🎛️ Panel 2 — Filters

> **Seven List/Dropdown Slicers** and a **Clear Filter** button, repeated at the top of every page.

| Control | Type | Field | Table |
|---|---|---|---|
| 📆 **Financial Year** | Dropdown Slicer | `Financial Year` | `DimDate` |
| 🗓️ **Quarter** | Dropdown Slicer | `Quarter` | `DimDate` |
| 📅 **MonthName** | Dropdown Slicer | `MonthName` | `DimDate` |
| 🌍 **Region** | Dropdown Slicer | `Region` | `DimBranch` |
| 🧭 **Zone** | Dropdown Slicer | `Zone` | `DimBranch` |
| 🏢 **BranchName** | Dropdown Slicer | `BranchName` | `DimBranch` |
| 🛍️ **ProductName** | Dropdown Slicer | `ProductName` | `DimProduct` |
| 🧹 **Clear Filter** | Button | — | Resets every slicer |

---

## 🎯 Panel 3 — Deposits vs Target

> **Page 1** — a Clustered Column Chart, a Line Chart, a Donut Chart, a Map and a drill-down Matrix.

| Visual | Type | Field Roles |
|---|---|---|
| 📊 Actual Deposits vs Target (Monthly) | Clustered Column | Axis `MonthName` · Values `Actual Deposits`, `Deposit Target` |
| 📈 Deposit Trend | Line Chart (Year > Quarter > Month) | Axis `Year`, `Quarter` · Values `Actual Deposits` |
| 🍩 Deposits By Product Type | Donut Chart (centre: **493bn**) | Legend `ProductName` · Values `DepositTarget` |
| 🗺️ Geographic Deposit Distribution (₹ Cr) | Map | Location `City` · Size `Actual Deposits` |
| 🧮 Deposit Performance By Branch Hierarchy | Matrix (Region > Zone > City > Branch) | `Actual Deposits`, `Deposit Target`, `Variance`, `Achievement %`, `YoY Growth %`, `Achievement Gap %` |

**🍩 Deposit products in the donut:** 🏠 Home Loan · 👤 Personal · 💼 Salary · 💰 Savings · 🚗 Vehicle

**🧮 Sample rows from the Branch Hierarchy matrix (Central region)**

| Zone | City | Branch | Actual Deposits | Deposit Target | Achievement % | YoY Growth % |
|---|---|---|---|---|---|---|
| Central | Ahmedabad | HDFC Branch 135 | ₹82 Cr | ₹2,268 Cr | 3.59% | 52.60% |
| East | Bengaluru | HDFC Branch 158 | ₹75 Cr | ₹1,988 Cr | 3.75% | 48.07% |
| North | Ahmedabad | HDFC Branch 1 | ₹67 Cr | ₹1,958 Cr | 3.44% | 47.92% |
| South | Ahmedabad | HDFC Branch 12 | ₹72 Cr | ₹1,945 Cr | 3.72% | 51.47% |
| West | Ahmedabad | HDFC Branch 104 | ₹45 Cr | ₹1,295 Cr | 3.44% | 52.17% |

> [!NOTE]
> **How to read it:** the trend chart peaks at about **₹152 Cr**, and each matrix row can be expanded from Region down to the individual branch.

> [!TIP]
> ✅ **Reading it:** within the Central region, **HDFC Branch 135** holds the highest deposits at **₹82 Cr**, while **Branch 158** has the best achievement at **3.75%**.

---

## 🏦 Panel 4 — Loan Portfolio

> **Page 2** — a Treemap, a Bar Chart, a Line Chart, a Map, a Donut Chart and a drill-down Matrix.

| Visual | Type | Field Roles |
|---|---|---|
| 🌳 Loan Portfolio By Product | Treemap | Group `ProductName` · Values `Total Loan Book` |
| 📉 Outstanding Loan Amount by Product | Clustered Bar | Axis `ProductName` · Values `Outstanding` |
| 💵 EMI Collection Trend | Line Chart (Year > Quarter > Month) | Axis `Year`, `Quarter`, `Month` · Values `EMI Collection` |
| 🗺️ Loan Exposure by Geography | Map | Location `City` · `Total Loan Book`, `NPA %` |
| 🚦 Loan Status Distribution | Donut Chart (centre: **4250**) | Legend `Status` · Values `Amount_Cr` |
| 🧮 Loan Portfolio Matrix | Matrix (Region > Zone > Branch) | `Loan Book PY`, `EMI Collection`, `Outstanding`, `NPA %` |

**🌳 Loan book and outstanding amount by product**

| Product | Loan Book | Outstanding | Visual |
|---|---|---|---|
| 🥇 Business Loan | ₹7,634 Cr | ₹7,557 Cr | 🟦🟦🟦🟦🟦🟦🟦🟦🟦🟦 |
| 🥈 Vehicle Loan | ₹7,615 Cr | ₹7,538 Cr | 🟦🟦🟦🟦🟦🟦🟦🟦🟦🟦 |
| 🥉 Home Loan | ₹7,575 Cr | ₹7,499 Cr | 🟦🟦🟦🟦🟦🟦🟦🟦🟦🟦 |
| 4️⃣ Education Loan | ₹7,575 Cr | ₹7,499 Cr | 🟦🟦🟦🟦🟦🟦🟦🟦🟦🟦 |
| 5️⃣ Personal Loan | ₹7,550 Cr | ₹7,474 Cr | 🟦🟦🟦🟦🟦🟦🟦🟦🟦🟦 |

**🚦 Loan Status** — 🟢 Current · 🟡 Delayed · 🔴 NPA · 🔵 Closed (the green *Current* band takes most of the ring).

**🧮 Loan Portfolio Matrix — Central and East regions**

| Region / Zone | Loan Book PY | EMI Collection | Outstanding | NPA % |
|---|---|---|---|---|
| **Central** | ₹4,908 Cr | ₹74 Cr | ₹7,269 Cr | 2.10% |
| ↳ Central | ₹1,161 Cr | ₹17 Cr | ₹1,714 Cr | 2.10% |
| ↳ East | ₹1,050 Cr | ₹16 Cr | ₹1,566 Cr | 2.10% |
| ↳ North | ₹1,057 Cr | ₹16 Cr | ₹1,564 Cr | 2.10% |
| ↳ South | ₹988 Cr | ₹15 Cr | ₹1,464 Cr | 2.10% |
| ↳ West | ₹651 Cr | ₹10 Cr | ₹961 Cr | 2.10% |
| **East** | ₹4,432 Cr | ₹66 Cr | ₹6,546 Cr | 2.10% |
| 🏁 **Total** | **₹25,274 Cr** | **₹383 Cr** | **₹37,567 Cr** | **2.10%** |

> [!TIP]
> ✅ **Reading it:** the five loan products are almost equal — each sits between **₹7.5K Cr and ₹7.6K Cr** — so no single product dominates the book.

---

## 🏢 Panel 5 — Branch Performance

> **Page 3** — a Map, a Bar Chart, a Column Chart and a drill-down Scorecard Matrix.

| Visual | Type | Field Roles |
|---|---|---|
| 🗺️ Branch Network Performance | Map | Location `City` · Size `Actual Deposits` |
| 💎 Revenue by Branch Hierarchy | Clustered Bar (Region > Zone > City > Branch) | Axis `Region`, `Zone`, `City`, `BranchName` |
| 🏢 Branch Type Performance | Clustered Column | Axis `BranchName` · `Actual Deposits`, `Total Loan Book` |
| 🧾 Branch Performance Scorecard | Matrix (Region > Zone > City > Branch) | `Total Deposits`, `Total Loan Book`, `Total Transactions`, `Achievement %` |

**💎 Revenue by Region**

| Region | Revenue | Visual |
|---|---|---|
| 🥇 North | ₹415 Cr | 🟧🟧🟧🟧🟧🟧🟧🟧🟧🟧 |
| 🥈 South | ₹370 Cr | 🟧🟧🟧🟧🟧🟧🟧🟧🟧 |
| 🥉 West | ₹342 Cr | 🟧🟧🟧🟧🟧🟧🟧🟧 |
| 4️⃣ Central | ₹340 Cr | 🟧🟧🟧🟧🟧🟧🟧🟧 |
| 5️⃣ East | ₹310 Cr | 🟧🟧🟧🟧🟧🟧🟧 |

**🏢 Branch Type Performance (sample branches)**

| Branch | Actual Deposits | Total Loan Book |
|---|---|---|
| HDFC Branch 94 | ₹4 Cr | ₹76 Cr |
| HDFC Branch 93 | ₹4 Cr | ₹76 Cr |
| HDFC Branch 96 | ₹4 Cr | ₹78 Cr |
| HDFC Branch 95 | ₹3 Cr | ₹83 Cr |
| HDFC Branch 97 | ₹3 Cr | ₹76 Cr |
| HDFC Branch 99 | ₹3 Cr | ₹71 Cr |
| HDFC Branch 92 | ₹3 Cr | ₹76 Cr |
| HDFC Branch 98 | ₹3 Cr | ₹77 Cr |

**🧾 Branch Performance Scorecard**

| Region | Total Deposits | Total Loan Book | Total Transactions | Achievement % | First Branch |
|---|---|---|---|---|---|
| 🥇 North | ₹415 Cr | ₹8,843 Cr | 115,743 | 3.62% | HDFC Branch 10 |
| 🥈 South | ₹370 Cr | ₹7,835 Cr | 103,556 | 3.63% | HDFC Branch 106 |

> [!TIP]
> ✅ **Reading it:** **North** leads on revenue (₹415 Cr), loan book (₹8,843 Cr) and transactions (115,743), and **Connaught Place Branch (New Delhi Zone)** is the best-performing branch.

---

## 💳 Panel 6 — Transactions

> A **Donut Chart** of transaction types (centre total **500K**) and a **Line Chart** of the daily trend on Page 3.

| Field Role | Field |
|---|---|
| Legend | `TransactionType` |
| Values | `Total Transactions` |

| Transaction Type | Share | Visual |
|---|---|---|
| 🥇 EMI | 14.39% | 🟪🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 🥈 ATM | 14.35% | 🟪🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 🥉 RTGS | 14.31% | 🟪🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 4️⃣ NEFT | 14.27% | 🟪🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 5️⃣ Withdrawal | 14.25% | 🟪🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 6️⃣ UPI | 14.22% | 🟪🟪🟪🟪🟪🟪🟪🟪🟪🟪 |
| 7️⃣ Deposit | 14.20% | 🟪🟪🟪🟪🟪🟪🟪🟪🟪🟪 |

**🔁 Transactions Trend** — a line chart that drills **Year → Quarter → Month → Day**, moving between roughly **0.40K and 0.50K** transactions per period from 2023 to 2025.

> [!NOTE]
> **How to read it:** the seven channels are almost evenly split (**14.2%–14.4% each**), so no single channel dominates.

---

## 🛠 Tech Stack

| Technology | Purpose |
|---|---|
| 📊 **Power BI Desktop** | Report authoring, data modelling and visual design |
| 🧮 **DAX** | Measures for achievement %, YoY growth, NPA %, EMI collection and transactions |
| 🧱 **Power BI Data Model** | Dimension tables (Branch, Date, Product) plus fact and target tables |
| 🧭 **Drill-down Hierarchies** | Region → Zone → City → Branch and Year → Quarter → Month → Day |
| 🗺️ **Map Visual** | Geographic deposits, loan exposure and branch performance |
| 🎨 **Native Visuals** | Card, Column, Bar, Line, Donut, Treemap, Map, Matrix, Slicer |
| 🖼️ **Custom Design** | Navy and red theme, icons, navigation buttons and a background watermark |

---

## 🏆 Results & Insights

| Panel | Key Insight |
|---|---|
| 💰 **KPI Cards** | Deposits **+14.18%**, loan book **+14.51%**, EMI collection **+14.97%**, transactions **+14.29%** vs previous year |
| 🎯 **Deposits vs Target** | Deposit target up **18.33%**; YoY deposit growth stands at **49.85%** |
| 🏦 **Loan Portfolio** | ₹37,949 Cr loan book across **77,775 active loans**; the five products are balanced at ₹7.5K–7.6K Cr each |
| ⚠️ **NPA %** | **NPA improved by 0.46%**, from 2.56% to **2.10%** |
| 🗺️ **Regional Revenue** | **North** leads at ₹415 Cr, then South (₹370 Cr); **East** is the lowest at ₹310 Cr |
| 💳 **Transactions** | 500K transactions split almost evenly across 7 channels (**14.2%–14.4%** each) |
| 🏆 **Top Branch** | **Connaught Place Branch (New Delhi Zone)** is the top performer with **128.40%** target achievement |
| 🏢 **Network** | Branch count grew **4.17%** to **500**; metro branches lead on both deposits and loans |

---

## 💡 Advantages

- ⚡ **Fully Interactive** — every card, chart and matrix responds to the 7 slicers, with no static exports
- 🎯 **Target-focused** — achievement %, variance and gap sit right beside actual deposits
- 🧭 **Drill-down Everywhere** — go from Region to Zone, City and Branch, or from Year down to Month and Day
- 🏦 **360° Bank View** — deposits, loans and branch activity in one report
- 🧮 **Centralised Measures** — all DAX lives in one `Measure Table`, easy to maintain
- 🗺️ **Map Views** — see where deposits, loans and branches concentrate
- 🎨 **Native Visuals Only** — opens cleanly in any standard Power BI Desktop install
- 🎬 **Presentation Included** — a Google Drive walkthrough explains the project end to end
- 🌱 **Room to Grow** — the model is ready for new pages such as customers, products or risk

---

## ▶️ How to Open & Use

1. 🎬 **[Watch the project presentation on Google Drive](https://drive.google.com/file/d/1fISE89XsNp_W9FODAEfjrGS7lPT0t_hT/view?usp=drive_link)** for a guided tour.
2. 💻 Install **Power BI Desktop** (free, Windows).
3. 📂 Open `HDFC_Bank_Dashboard.pbix`. The data is stored inside the file, so the visuals load immediately.
4. 🧭 Use the **sidebar buttons** to switch between *Deposits vs Target*, *Loan Portfolio* and *Branch Performance*.
5. 🖱️ Pick values in the **slicers** to filter every visual, or click a chart segment to cross-filter the rest of the page. Press **Clear Filter** to reset.
6. 🔍 Use the **drill arrows** on charts and the **+ / −** icons in the matrices to move through the hierarchies.

---

## 🎬 Project Presentation

<div align="center">

<a href="https://drive.google.com/file/d/1fISE89XsNp_W9FODAEfjrGS7lPT0t_hT/view?usp=drive_link">
  <img src="assets/video_thumbnail.png" alt="Click to watch the Project Presentation" width="760"/>
</a>

**👆 Click the thumbnail to watch the full project presentation on Google Drive**

[![Watch on Google Drive](https://img.shields.io/badge/Google_Drive-Watch_the_Presentation-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1fISE89XsNp_W9FODAEfjrGS7lPT0t_hT/view?usp=drive_link)

</div>

| 🎞️ Detail | Info |
|---|---|
| ☁️ **Hosted on** | Google Drive |
| 🏦 **Project** | HDFC Bank Dashboard |
| 📄 **Pages covered** | Deposits vs Target · Loan Portfolio · Branch Performance |
| 🛠️ **Built with** | Power BI Desktop and DAX |

**What the project covers**

| Step | What you will see |
|:---:|---|
| 💰 **1** | The **Deposits vs Target** page — KPI cards, monthly actual vs target, deposit trend, product mix, map and branch hierarchy matrix |
| 🏦 **2** | The **Loan Portfolio** page — loan book, EMI collection, NPA %, product treemap, loan status and portfolio matrix |
| 🏢 **3** | The **Branch Performance** page — branch map, revenue by region, transaction types and the branch scorecard |
| 🎛️ **4** | **Live filtering** with the 7 slicers — every card and chart updates together |

---

## 🖼️ Dashboard Preview

<div align="center">

### 🟥 Page 1 — Deposits vs Target

<img src="Page 1 - Deposits vs Target Dashboard.png" alt="HDFC Bank — Deposits vs Target Dashboard" width="900"/>

*KPI cards on top, filters above them, then monthly actual vs target, deposit trend, product mix, map and the branch hierarchy matrix.*

<br/>

### 🟦 Page 2 — Loan Portfolio Breakdown

<img src="Page 2 - Loan portfolio Breakdown.png" alt="HDFC Bank — Loan Portfolio Breakdown" width="900"/>

*Loan book, active loans, EMI collection and NPA % cards, with the product treemap, status donut and portfolio matrix.*

<br/>

### 🟩 Page 3 — Branch Performance

<img src="Page 3 - Branch Performance dashboard.png" alt="HDFC Bank — Branch Performance Dashboard" width="900"/>

*Branch network map, revenue by region, transaction trend and types, branch type performance and the scorecard.*

</div>

---

## 📄 License

```
MIT License

Copyright (c) 2026

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.
```

---

## 👩‍💻 Author

<div align="center">

| | |
|---|---|
| 👤 **Name** | _KRINA GHORI_ |
| 📊 **Tool** | Power BI Desktop |
| 📁 **Project** | HDFC Bank Dashboard |
| 💡 **Purpose** | Interactive deposits, loan and branch performance analytics dashboard |

<br/>

Made with 💙 using **Power BI**

![Power BI Love](https://img.shields.io/badge/Made%20with-%F0%9F%92%99%20Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

</div>

---

## 🙏 Acknowledgements

- 📊 **Microsoft Power BI Team** — for the report engine and visualization framework behind this dashboard
- 🏦 **HDFC Bank** — the bank whose branding and banking domain inspired this analytics project
- 📖 **Power BI Documentation** — for reference on DAX, drill-down hierarchies, matrices and native chart visuals
- 💻 **Open Source Community** — for README badge tools (shields.io) and typing SVG animations
- 🎓 **All learners** — who build dashboards like this to sharpen their BI fundamentals

---

<div align="center">

⭐ **Star this repo if you found it helpful!** ⭐

</div>
