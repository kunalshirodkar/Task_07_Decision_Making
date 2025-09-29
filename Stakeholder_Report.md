# 🥍 Syracuse Women’s Lacrosse Stats – Stakeholder Report

## 🎯 Objective
Analyze Syracuse Women’s Lacrosse 2024 season statistics to identify top performers and trends, and showcase how AI/LLM tools accelerated the analysis process.

---

## 📊 Data Overview

- **Source**: Syracuse Women’s Lacrosse Stats (Excel format)
- **Rows**: 32 players
- **Key Columns**:
  - Goals (G), Assists (A), Points (PTS)
  - Shots, Shots on Goal (SH, SOG)
  - Caused Turnovers (CT), Ground Balls (GB), Draw Controls (DC)

---

## 🧼 Cleaning Steps

- Removed blank rows and standardized column names
- Split `GP-GS` (Games Played-Games Started) into two columns
- Split `RC-YC-GC` (Red Card-Yellow Card-Green Card) into separate fields
- Handled missing values for goalkeepers (GK-specific stats)

---

## 📈 Visual Insights

- **Top 10 Players by G+A**  
  Stacked bar chart using dark green (Goals) and purple (Assists) from `viridis` palette

- **Donut Chart for CT**  
  Displayed top 10 players by caused turnovers

- **Boxplot of Goals by Shot Group**  
  Helped identify efficiency trends

- **Histogram of Shot Attempts**  
  Distribution of total shooting activity

---

## 🤖 Use of AI/LLM Tools

This project heavily utilized **LLM-based assistance (ChatGPT)** for:

- Designing custom Python/Seaborn code
- Debugging data cleaning logic
- Selecting visually appealing color palettes
- Suggesting effective plot types
- Writing markdown documentation & summaries

LLMs significantly **accelerated the workflow** by reducing the need to search for syntax or libraries, making this a great example of **decision-making with modern AI tools**.

---

## 🔚 Conclusion

This analysis helps coaches and stakeholders identify standout performers and tactical patterns. With AI support, the end-to-end analysis was both **faster** and more **insightful**, demonstrating the power of LLMs in data-driven decision-making workflows.

---

