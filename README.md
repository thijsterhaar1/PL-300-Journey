# PL-300-Journey – Thijs ter Haar

This is my learning and practice repo for **Microsoft PL-300: Power BI Data Analyst**.   I use this repo to track my progress, store projects, and organize my notes.

---

## Goals

- Pass the PL-300 certification exam  
- Build several clean Power BI dashboards I can use as a portfolio  
- Improve my skills in:
  - Data preparation (Power Query)
  - Data modeling (relationships, star schema)
  - DAX (measures, CALCULATE, etc.)
  - Visualizations & reporting in Power BI
  - Power BI Service, sharing & security (RLS)

---

## Progress checklist (PL-300 topics)

### 1. Prepare the data

- [ ] Connect to different data sources (Excel, CSV, SQL, etc.)
- [ ] Power Query basics (filtering, sorting, setting data types)
- [ ] Split, merge and remove columns
- [ ] Merge & append tables
- [ ] Conditional columns / custom columns
- [ ] Clean up errors and null values

### 2. Model the data

- [ ] Create relationships (one-to-many, direction, cardinality)
- [ ] Understand star schema (fact / dimension tables)
- [ ] Know when to use calculated columns vs measures
- [ ] Basic DAX:
  - [ ] `SUM`, `COUNT`, `AVERAGE`
  - [ ] `CALCULATE`
  - [ ] `FILTER`
  - [ ] `RELATED`
- [ ] Simple time intelligence (YTD, MTD, QoQ)

### 3. Visualize & analyze the data

- [ ] Core visuals (bar/column chart, line chart, table, matrix)
- [ ] Slicers and filters (visual / page / report level)
- [ ] Drillthrough & tooltips
- [ ] Sorting & grouping
- [ ] Conditional formatting
- [ ] Build KPIs / Cards for management views

### 4. Manage & secure Power BI

- [ ] Work with Power BI Service (workspaces, datasets, reports, apps)
- [ ] Dataset refresh (scheduled refresh, gateways – at a high level)
- [ ] Set up Row-Level Security (RLS)
- [ ] Create roles and test them with “View as role”
- [ ] Basic sharing & permissions

---

## Projects

I keep my practice projects in the [`projects/`](./projects) folder.

1. **Sales Dashboard v1**
   - Topics: data cleaning, basic data model, slicers, bar/line charts
   - File: `projects/sales-dashboard-v1/sales-dashboard-v1.pbix`
   - Screenshot: `screenshots/sales-dashboard-v1.png`

> More projects will be added as I build new exercises and dashboards.

---

## Repository structure

High-level layout of this repo:

- `notes/` – Markdown notes per topic (prepare, model, visualize, manage & secure)
- `projects/` – Power BI projects (.pbix) + a separate README per project
- `checklists/` – Checklists & exam objectives I can tick off
- `screenshots/` – Screenshots of dashboards I might use in a portfolio later
- `README.md` – This file, with my overview and progress

---

## Commit messages

I try to use short and clear commit messages, such as:

- `notes: add prepare-data basics`
- `feat: add sales dashboard v1`
- `chore: update progress checklist`

---

## Next steps

- Work through the Microsoft Learn modules for PL-300  
- Build at least one small project for each major topic  
- Do the practice exam & additional sample questions  
- Finally: schedule and pass the PL-300 exam ✅
