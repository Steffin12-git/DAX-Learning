# 📊 Learning DAX

Welcome to **Learning DAX**, a curated, practical guide to help you master the essential 80% of **DAX (Data Analysis Expressions)** — the powerful formula language behind Power BI, Excel Power Pivot, and Analysis Services.

This repository is designed for anyone looking to build strong foundational knowledge in DAX with hands-on examples and simple explanations.

---

## 🚀 What You'll Learn

* **✅ Measures vs. Calculated Columns**
  Understand when and why to use each, with clarity on storage and performance.

* **📐 Evaluation Contexts**
  Grasp the difference between **row context** and **filter context**, and how they impact your formulas.

* **🔁 Reusable Calculations (Measures)**
  Create dynamic, reusable logic with DAX measures that automatically adjust to filters.

* **🧠 Core DAX Functions**
  Learn and apply essential DAX functions:

  * `SUM()`, `AVERAGE()`, `COUNTROWS()`, `DIVIDE()`
  * Conditional logic with `IF()`, `SWITCH()`
  * Advanced filtering with `CALCULATE()`

* **🔄 Context Transition**
  Learn how filter context transforms in calculated fields and visuals.

* **📊 Dynamic Filtering with CALCULATE**
  Use `CALCULATE()` to modify context and write powerful custom measures.

---

## 📁 Sample Use Case

```dax
-- Total Sales using a measure
Total Sales = SUM(Sales[Amount])

-- Conditional logic
High Sales Flag = IF([Total Sales] > 5000, "High", "Low")

-- Dynamic filter with CALCULATE
APAC Sales = CALCULATE([Total Sales], Geo[Region] = "APAC")
```

---

## 🎯 Who This Is For

* 💡 **Beginners** who want to demystify DAX logic.
* 📊 **Data Analysts** eager to enhance their Power BI skills.
* 🧪 **SQL/Excel users** transitioning to Power BI or Analysis Services.

---

## 📌 Tips for Mastering DAX

* Think **in terms of context**, not just values.
* Use **measures** over calculated columns when possible.
* Practice with **small datasets** and visualize your filters.
* Explore, break, and fix – **trial and error is your teacher**.

---

## 📚 Further Resources

* [DAX Guide](https://dax.guide/) – A searchable reference for all DAX functions.
* [DAX Patterns](https://www.daxpatterns.com/) – Solutions to common modeling problems.
* [VertiPaq Analyzer](https://www.sqlbi.com/tools/dax-studio/) – Optimize your DAX and data model.

---

## 🤝 Contributions Welcome

Have improvements, corrections, or ideas?
Feel free to open an issue or submit a pull request. Let’s build the best free DAX learning resource together.

---

### 🧠 Start mastering DAX now and power up your data storytelling!