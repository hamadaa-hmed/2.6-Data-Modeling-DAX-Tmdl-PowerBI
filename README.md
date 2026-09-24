# 📊 Power BI — DAX, TMDL & Data Transformation Practice

A practical **Power BI project** focused on learning and applying core techniques for **data transformation, calculated columns, conditional logic, DAX, Calendar tables, Measures, and TMDL**.

The project demonstrates the workflow of preparing data, building calculations, creating a structured date table, defining analytical measures, and using the resulting model in a Power BI dashboard.

---

## 🎯 Project Objective

The main goal of this project is to practice and demonstrate important **Power BI Data Modeling and DAX concepts** rather than focusing on a specific business case.

The project covers:

- Data transformation with **Custom Columns**
- Business logic with **Conditional Columns**
- Creating a **Calendar table using DAX**
- Creating and organizing **DAX Measures**
- Working with **TMDL**
- Building and using a structured **Power BI semantic model**
- Presenting the results through a **Dashboard**

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **Power Query**
- **DAX**
- **DAX Calendar**
- **TMDL (Tabular Model Definition Language)**
- **Data Modeling**
- **Data Visualization**

---

## 🔄 Project Workflow

```text
Raw Data
   ↓
Power Query
   ↓
Custom Columns
   ↓
Conditional Columns
   ↓
Data Modeling
   ↓
DAX Calendar
   ↓
DAX Measures
   ↓
TMDL
   ↓
Dashboard
```

---

## 🧮 1. Custom Columns

Custom columns were created to generate new values from existing fields.

### Example

A **Revenue** column can be calculated using:

```text
Revenue = Units × Unit Price
```

This demonstrates how Power Query can be used to create calculated fields during the data preparation stage.

---

## 🔀 2. Conditional Columns

Conditional logic was used to create a new classification column based on business rules.

For example, profit margin can be categorized into different groups such as:

```text
Loss
Low
Medium
High
```

This demonstrates how raw numerical values can be transformed into meaningful categories for analysis.

---

## 📅 3. DAX Calendar Table

A dedicated **Calendar table** was created using DAX to support time-based analysis.

The Calendar includes useful date attributes such as:

- Date
- Day
- Day Name
- Day Number
- Week Number
- Month
- Month Name
- Year

The month fields are also organized so that **Month Name can be sorted by Month Number**, ensuring the correct chronological order in visuals.

---

## 📐 4. DAX Measures

Multiple DAX Measures were created as part of the project.

The measures are used to perform calculations dynamically within the Power BI model and support the dashboard and analytical visuals.

This section demonstrates practical use of:

- DAX aggregation
- Calculated metrics
- KPI calculations
- Filter context
- Reusable Measures

---

## 🧩 5. TMDL

The project also explores **TMDL — Tabular Model Definition Language**.

TMDL provides a text-based way to work with the Power BI semantic model and its metadata.

The project uses TMDL as part of the modeling workflow to practice working with model objects such as:

- Tables
- Columns
- Measures
- Model structure
- Metadata

This provides practical experience beyond working only through the Power BI graphical interface.

---

## 📊 6. Dashboard

The final stage is presenting the prepared data model and DAX calculations through a Power BI dashboard.

The dashboard brings together:

- Calculated values
- Categories
- KPIs
- Date-based analysis
- DAX Measures
- Data visualizations

The purpose of the dashboard is to demonstrate how the modeling and calculation techniques can be used together in a practical Power BI report.

---

## 💡 Key Learning Outcomes

Through this project, I practiced:

- Transforming data using **Power Query**
- Creating **Custom Columns**
- Creating **Conditional Columns**
- Building a **DAX Calendar table**
- Creating and organizing **DAX Measures**
- Understanding **date-based modeling**
- Working with **TMDL**
- Structuring a **Power BI semantic model**
- Connecting data modeling with dashboard visualization

---

## 📂 Project Structure

```text
📦 Power-BI-DAX-TMDL-Analytics
│
├── 📊 PowerBI/
│   └── Project.pbix
│
├── 📁 Data/
│   └── dataset.csv
│
├── 🖼️ Images/
│   ├── dashboard.png
│   └── analysis.png
│
├── 🎥 Demo/
│   └── project-demo.mp4
│
└── 📄 README.md
```

---

## 🖼️ Project Preview

Add screenshots of the Power BI report here:

```markdown
![Power BI Dashboard](Images/dashboard.png)
```

---

## 🎥 Project Demo

A project demonstration is included to show the workflow, calculations, modeling steps, and final Power BI report.

---

## 🎓 Skills Demonstrated

**Power BI · Power Query · DAX · TMDL · Data Modeling · Data Transformation · Calculated Columns · Conditional Logic · Calendar Tables · Measures · Data Visualization**

---

## 📌 Conclusion

This project is a practical exploration of the Power BI modeling workflow, combining **Power Query transformations, DAX calculations, Calendar modeling, Measures, and TMDL** into one project.

It demonstrates how different Power BI features work together to transform raw data into a structured semantic model and an interactive dashboard.

---

⭐ **Power BI | DAX | TMDL | Data Modeling | Data Transformation**
