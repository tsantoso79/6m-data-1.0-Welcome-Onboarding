# **Module 1 Course Content Plan**

Methodology: Flipped Classroom (AI-Assisted Pre-study)

Session Structure: 20-25 minute "Sprints" (Recap \+ Hands-on)

## **📍 Phase 1: Onboarding & Foundations**

### **Class 1: Welcome \+ Introduction \+ Onboarding (Onsite)**

**Goal:** Cultural alignment, Environment setup, and "Learning to Learn".  
The learners’ role in this module: data scientist intern, and tasked to complete a data analysis for a job market insight report. 

* **9:00 \- 9:45:** **The "Why" & The "How":** Course Roadmap, The "Flipped" Philosophy, and Introducing Google NotebookLM.  
* **9:45 \- 10:30:** **Workshop:** Setting up Google Colab & Accessing the LMS.  
* **10:30 \- 11:00:** **Activity:** "Prompt Engineering 101." Students practice asking NotebookLM to summarize a technical article.  
* **11:00 \- 11:45:** **Icebreaker Data Collection:** Students update self-intro deck; (which we will analyze later in the course).   
* **11:45 \- 12:00: How to get Help? Discord setup.**

### **Class 2 (1.1): Intro to Data Science (Virtual)**

**Goal:** Understanding the Data Lifecycle.

* **Pre-Study:** Read "The Data Science Hierarchy of Needs". Ask NotebookLM: *"What is the difference between Data Analytics, Data Science, and AI?"*  
* **Sprint 1:** **The Data Pipeline.** (Collection \-\> Cleaning \-\> Analysis \-\> Viz).  
* **Sprint 2:** **Types of Data.** Structured (Excel) vs. Unstructured (Images/Text).  
* **Sprint 3:** **The Role of Ethics.** Bias in data.  
* **Sprint 4:** **Case Study Review.** How Netflix uses data (Group discussion).

## **🗄️ Phase 2: SQL & Databases**

### **Class 3 (1.2): Introduction to Database (Virtual)**

**Goal:** Conceptualizing the Relational Model.

* **Pre-Study:** Ask NotebookLM: *"Explain Primary Keys and Foreign Keys using a library analogy."*  
* **Sprint 1:** **Tables, Rows, Columns.** The Excel analogy.  
* **Sprint 2:** **Relational Design.** Why split data into multiple tables? (Normalization Lite).  
* **Sprint 3:** **Key Concepts.** Primary Key (ID) vs Foreign Key (Link).  
* **Sprint 4:** **ER Diagrams.** Reading a simple schema map.

### **Class 4 (1.3): SQL Basic \- DDL (Data Definition Language) (Virtual)**

**Goal:** Building the buckets (Tables).

* **Pre-Study:** Ask NotebookLM: *"What is the difference between DDL and DML in SQL?"*  
* **Sprint 1:** **Data Types.** INT, VARCHAR, DATE, BOOLEAN.  
* **Sprint 2:** **CREATE TABLE.** Writing the blueprint.  
* **Sprint 3:** **Constraints.** NOT NULL, UNIQUE.  
* **Sprint 4:** **ALTER TABLE.** Adding a forgotten column.  
* **Sprint 5:** **DROP/TRUNCATE.** The danger zone (Deleting tables).

### **Class 5 (1.4): SQL Basic \- DML (Data Manipulation Language) (Virtual)**

**Goal:** Filling and modifying the buckets.

* **Pre-Study:** Ask NotebookLM: *"Write a cheat sheet for SQL CRUD operations."*  
* **Sprint 1:** **INSERT.** Adding single and multiple rows.  
* **Sprint 2:** **SELECT (The Basics).** SELECT \* vs SELECT specific\_cols.  
* **Sprint 3:** **UPDATE.** Changing existing data (and the importance of WHERE).  
* **Sprint 4:** **DELETE.** Removing specific rows.  
* **Sprint 5:** **Review.** A full CRUD cycle (Create, Read, Update, Delete) exercise.

### **Class 6 (C1.1): Coaching (GitHub) (Onsite) \+ VS/WSL installation**

**Goal:** Version Control for Collaboration.

* **Format:** Workshop Style (Less structured sprints, more guided follow-along).  
* **Part 1:** **Git Concepts.** Repositories, Commits, Push/Pull.  
* **Part 2:** **The Setup.** Installing Git/Connecting VS Code (if applicable) or using GitHub Desktop.  
* **Part 3:** **The Workflow.** git add \-\> git commit \-\> git push.  
* **Part 4:** **Conflict Resolution.** What happens when two people edit the same file?

### **Class 7 (1.5): SQL Advanced (Virtual)**

**Goal:** Complex Analysis.

* **Pre-Study:** Ask NotebookLM: *"Explain SQL Joins with Venn Diagrams."*  
* **Sprint 1:** **Aggregations.** COUNT, SUM, AVG.  
* **Sprint 2:** **GROUP BY.** Segmenting data.  
* **Sprint 3:** **HAVING vs WHERE.** Filtering before vs after aggregation.  
* **Sprint 4:** **JOINS (Inner vs Left).** Connecting tables.  
* **Sprint 5:** **Subqueries (Intro).** Using a query result inside another query.

## **🐍 Phase 3: Python & Numerical Analysis**

### **Class 8 (1.6): Introduction to Numpy (Virtual)**

**Goal:** fast math and matrices (Pre-cursor to Pandas).

* **Pre-Study:** Ask NotebookLM: *"Why is NumPy faster than Python lists?"*  
* **Sprint 1:** **Lists vs Arrays.** Memory and speed.  
* **Sprint 2:** **Creating Arrays.** np.array, np.zeros, np.arange.  
* **Sprint 3:** **Vectorization.** Doing math on whole arrays at once (no loops\!).  
* **Sprint 4:** **Indexing/Slicing.** Grabbing parts of a matrix.  
* **Sprint 5:** **Basic Stats.** Mean, Median, Std Dev with NumPy.

### **Class 9 (C1.2): Coaching (Onsite)**

**Goal:** Mid-point consolidation.

* Review of SQL vs Python logic.  
* Troubleshooting environmental issues.  
* Hands-on Lab: Solving a hybrid problem (Designing a table on paper, then calculating stats in NumPy).

### **Class 10 (1.7): Introduction to Pandas (Virtual)**

**Goal:** The "Excel Killer" \- Working with Tabular Data.

* **Pre-Study:** Ask NotebookLM: *"Explain the relationship between a Series and a DataFrame in Pandas."*  
* **Sprint 1:** **The DataFrame.** Loading CSVs.  
* **Sprint 2:** **Inspection.** .info(), .describe(), .head().  
* **Sprint 3:** **Selection.** .loc vs .iloc.  
* **Sprint 4:** **Filtering.** Conditional logic (df\[df\['age'\] \> 30\]).  
* **Sprint 5:** **Sorting & Ranking.**

## **🔎 Phase 4: Exploratory Data Analysis (EDA)**

### **Class 11 (1.8): Exploratory Data Analysis (EDA) Basic (Virtual)**

**Goal:** Cleaning the mess.

* **Pre-Study:** Ask NotebookLM: *"What are the most common data quality issues?"*  
* **Sprint 1:** **Handling Nulls.** isnull(), dropna(), fillna().  
* **Sprint 2:** **Duplicates.** Finding and removing.  
* **Sprint 3:** **Data Typing.** Converting Strings to Numbers/Dates.  
* **Sprint 4:** **Renaming & Reordering.** Tidying up columns.  
* **Sprint 5:** **String Manipulation.** Cleaning text data.

### **Class 12 (C1.3): Coaching (Onsite)**

**Goal:** Practical Application Lab.

* **Activity:** "The Dirty Data Challenge." Students are given a deliberately broken dataset and must compete to clean it perfectly using the skills from Classes 10 & 11\.

### **Class 13 (1.9): EDA Advanced (Virtual)**

**Goal:** Deep Dive Analysis.

* **Pre-Study:** Ask NotebookLM: *"What is correlation in data analysis?"*  
* **Sprint 1:** **Grouping (Pandas).** .groupby() syntax.  
* **Sprint 2:** **Pivot Tables.** Using pd.pivot\_table.  
* **Sprint 3:** **Merging.** pd.merge (The Python version of SQL Joins).  
* **Sprint 4:** **Correlation Matrix.** Finding relationships.  
* **Sprint 5:** **Feature Engineering.** Creating new columns from existing ones (e.g., extracting "Year" from "Date").

### **Class 14 (1.10): Data Visualization (Virtual)**

**Goal:** Visual Storytelling.

* **Pre-Study:** Ask NotebookLM: *"When should I use a bar chart vs a line chart vs a scatter plot?"*  
* **Sprint 1:** **Matplotlib Basics.** The anatomy of a figure.  
* **Sprint 2:** **Seaborn Intro.** Making it look pretty easily.  
* **Sprint 3:** **Distributions.** Histograms and Boxplots.  
* **Sprint 4:** **Relationships.** Scatter plots and Heatmaps.  
* **Sprint 5:** **Customization.** Titles, Labels, Colors.

## **🏆 Phase 5: Conclusion**

### **Class 15 (C1.4): Coaching / Capstone Presentation (Onsite)**

**Goal:** Demonstrating the "1 Million Row" Learning Outcome.

* **0:00 \- 1:30:** **Final Prep.** Instructors float to help with final dashboard tweaks.  
* **1:30 \- 2:30:** **Presentations.** Each student/group presents 1 key insight from the massive dataset.  
* **2:30 \- 3:00:** **Graduation & Next Steps.** How to keep learning.