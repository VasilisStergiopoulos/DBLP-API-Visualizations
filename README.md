# 📘 DBLP-API-Visualizations
A data-driven analytics project using the DBLP API to retrieve, clean, and visualize academic publication data for Computer Science authors.
Developed as part of coursework at International Hellenic University.

This project demonstrates how to:
  - Collect publication metadata from the DBLP API
  - Handle pagination / multi-page author results
  - Parse JSON responses into pandas DataFrames
  - Analyze publication patterns over time
  - Build multiple visualizations (Bar, Line, Pie, Network Graph)

---

🚀 Project Overview
The notebook DBLP_API.ipynb performs the full workflow:

1️⃣ Data Collection
- Requests publication data using the DBLP RESTful API
- Handles pagination to retrieve all results
- Parses JSON into structured pandas DataFrames

2️⃣ Data Exploration & Visualizations
The project includes several visual analyses:

📊 Publication Analytics
- Total number of publications (Bar Plot)
- Publications over time (Line Plot)
- Publication types (Pie Chart)
- Distribution across venues (Bar Plot)

🏛 Venue-Based Insights
- Most popular venues per year (Bar Plot)

👥 Co-Authorship Insights
- Most frequent collaborators (Network Graph + Bar Plot)

These visualizations help understand:
-author productivity trends
- venue preferences
- collaboration patterns
- evolution of work over time

---

📁 Repository Structure

```
DBLP-API-Visualizations/
── notebook/
  │     └── DBLP_API.ipynb
  ├── results/
  │     └── plots/        # exported PNG visualizations
  ├── README.md
  └── requirements.txt
```
