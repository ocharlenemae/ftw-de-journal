# 📓 Journal - 2026-08-29
### 🔄 Spark & Transformation

---

## 💡 Today in One Sentence
> *Complicated tools and fancy visuals are NOT always the answer.*

> **Takeaway:** Spark handles huge datasets easily, but the golden rule is to use the simplest tool to SOLVE THE PROBLEM. The same idea applies to dashboards. If a fancy chart cannot make its point in under 10 seconds, it is a waste of space.

---

## 🧠 What I Learned
- **Spark is an execution engine, NOT a language**
    - Processes massive data across clusters, but moving data between nodes takes TIME 
    - Use *PySpark* (Python) and *Spark SQL* to code in it
    - Switch to Spark over regular SQL databases whenever our data volume or logic gets too massive for just one computer 
- **SQL is still the bread and butter for DEs** (just cooler if you know how to code with Spark 😎)
    - If SQL can solve the problem, stick with it and save yourself the Spark headaches ☺️
- **VS Code is the standard tool for local development** 
    - Writing code directly in production tools like Databricks is risky because one wrong script can BREAK the database! 
- **Data Quality is a core pipeline step, NOT an afterthought!**
    - Apply checks (`UNIQUE`, `NULL`, `RANGE`, `ACCEPTED VALUES`, `REFERENTIAL INTEGRITY`, `VOLUME`) across every layer (Bronze, Silver, Gold)
    - Use `PASS`, `WARN`, and `REJECT` status levels based on business rules to keep data clean

---

## 📚 Terms I Am Still Learning
- **Data Profiling 📊** — checking raw data statistics (min, max, null counts, frequencies) to see how healthy it is before building anything
- **Data Quality 🛡** — enforcing rules and limits on live data based on what was found during data profiling

---

## ❓ What Confused Me
- Realizing I was mixing up data profiling with data quality the whole time
- I still struggle to grasp why VS Code is so essential for staging and local development when we can already create sandbox branches directly in GitHub 👉👈
- Writing all six data quality checks into one clean script (definitely just a skill issue 😅)

---

## 🎯 One Small Next Step
- [ ] Code the exercise earlier in PySpark completely on my own (no hints/help!)
- [ ] Learn how to orchestrate Databricks Jobs 
- [ ] Master basic navigation, workspace setups, and Git branching inside VS Code
- [ ] Learn dbt fundamentals and transformation theories

---

## ⚙️ Git Checkpoint
- [x] Pushed a single scoped commit for my task (unless someone drops a last-minute comment or update 😆)
- [x] Strictly worked inside my isolated sandbox branch

---

## 🪞 Reflection
- **What felt easy today?** Learning the six data quality check types (loved having a standard format for data validation!).
- **What felt difficult today?** Writing in PySpark and setting up data quality tables under 30 minutes
- **What do I want to understand better next time?** VS Code navigation and Git workflows

---

## ✨ Mood or Meme
> *Still getting better with GitHub. Promise that I will learn VS Code soon, but for now ... testing live in production!*

![Production Meme](/assets/production.jpg)
