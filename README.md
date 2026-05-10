# 📊 Power BI — Data Professional Survey Dashboard

A Power BI dashboard project built while learning Power BI from scratch. Followed Alex The Analyst's walkthrough as a guide but worked through the data transformation, DAX logic, and visual layout independently — understanding the reasoning behind each step rather than just replicating the output.

The goal was to get comfortable with Power BI's full workflow: loading raw data, cleaning it in Power Query, building measures, and designing a readable dashboard before moving into independent projects.

Dataset source: [Alex The Analyst — Data Professional Survey](https://github.com/AlexTheAnalyst/Power-BI)

---

## 🛠️ Tools Used

- **Power BI Desktop** — data transformation, modelling, and dashboard design
- **Power Query** — cleaning and reshaping raw survey data
- **DAX** — calculated measures for averages and salary midpoints
- **Dataset** — 630 survey responses from data professionals globally (role, salary, language preference, happiness scores, demographics)

---

## 🔍 What This Project Covers

### 1. Data Transformation in Power Query
- Split and cleaned freetext responses in the salary and job title columns
- Extracted numeric midpoints from salary range buckets (e.g. `41k-65k` → `53`) to enable average calculations
- Trimmed and standardised inconsistent entries across role and country fields
- Removed irrelevant metadata columns (browser, OS, referrer) that added no analytical value

### 2. DAX Measures
- Created calculated measures for average salary by job title
- Calculated average happiness scores across six dimensions: salary, work/life balance, coworkers, management, upward mobility, and learning

### 3. Dashboard Design
- Built a single-page interactive dashboard with slicers, KPI cards, bar charts, donut charts, and a treemap
- Laid out visuals to guide the viewer logically: who responded → what they earn → what tools they use → how satisfied they are

---

## 📊 Key Findings

- **630 respondents** | Average age: **29.9 years** | Top country: **United States (41%)**
- **Python dominates** as the favourite language at 67% — R is a distant second at 16%
- **59%** of respondents switched into data from a different career
- **Salary satisfaction scored the lowest** of all six happiness dimensions (avg 4.27/10) — data professionals broadly feel underpaid relative to their work
- Work/life balance and coworker satisfaction scored highest, both above 5.7/10

---

## 📂 Files

| File | Description |
|------|-------------|
| `Project-WT01.pbix` | Power BI Desktop file — full dashboard |
| `Power_BI_-_Final_Project.xlsx` | Raw survey dataset |
| `screenshots/` | Dashboard preview images |

> **Note:** To open the `.pbix` file, Power BI Desktop is required (free download from Microsoft). Screenshots are provided above for quick reference.

---

## 💡 Key Techniques Used

`Power Query` · `Data Transformation` · `Column Splitting` · `DAX Measures` · `Calculated Columns` · `KPI Cards` · `Slicers` · `Bar Charts` · `Donut Charts` · `Treemap` · `Dashboard Layout`

---
