# Statistics for Data Analysis using Microsoft Excel 📊

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Excel Version: 2016 / 2019 / 365](https://img.shields.io/badge/Excel-2016%20%7C%202019%20%7C%20365-green.svg)](https://www.microsoft.com/en-us/microsoft-365/excel)
[![Course Duration: 90 Mins](https://img.shields.io/badge/Duration-1h%2030m%20(90%20Mins)-orange.svg)](#course-schedule)
[![Live Slide Deck](https://img.shields.io/badge/Interactive%20Slides-GitHub%20Pages-purple.svg)](https://ahmed-muhammed80.github.io/Statistics-for-Data-Analysis-Excel/)

A complete, beginner-friendly 90-minute curriculum, interactive web slide deck, and instructor facilitation guide for teaching **Statistics for Data Analysis using Microsoft Excel**. 

Designed for aspiring data analysts, business intelligence beginners, and non-mathematicians. The course focuses on **Descriptive Statistics**—learning how to summarize, understand, compare, and communicate dataset stories using Excel formulas rather than academic mathematical theory.

---

## 🌐 Interactive Presentation Slide Deck

Click below to launch the live interactive slide deck directly in your browser:

👉 **[Launch Interactive Slide Deck (GitHub Pages)](https://ahmed-muhammed80.github.io/Statistics-for-Data-Analysis-Excel/)**

### Slide Features:
- 📺 **Fullscreen Mode:** Press `F` to enter full presentation mode.
- 🎙️ **Speaker Notes Drawer:** Press `N` to toggle instructor notes and verbal prompts live on screen.
- ⌨️ **Keyboard Navigation:** Use `Arrow Left` / `Arrow Right` or `Spacebar` to navigate.

---

## 📁 Repository Structure

```text
Statistics-for-Data-Analysis-Excel/
├── README.md                              # Main course documentation & GitHub overview
├── index.html                             # Interactive Web Slide Deck (GitHub Pages ready)
├── docs/
│   ├── INSTRUCTOR_FACILITATION_GUIDE.md   # 90-minute master lesson plan & scripted teaching guide
│   ├── LESSON_SLIDES_OUTLINE.md           # Markdown version of slides (for PowerPoint/Keynote export)
│   ├── CHEAT_SHEET.md                     # Quick reference statistics & Excel formula cheat sheet
│   └── STUDENT_CHALLENGE_ANSWER_KEY.md    # Challenge questions & detailed instructor answer key
└── exercises/
    ├── EXCEL_HANDSON_WORKSHOP_TASKS.md    # Guided 6-step Excel workshop exercises for students
    └── sample_health_data.csv             # 100-row sample dataset for immediate classroom practice
```

---

## 🎯 Learning Objectives

By the end of this 90-minute session, students will be able to:

1. **Explain** what statistics means in a practical data analytics context.
2. **Distinguish** between *Descriptive Statistics* (what happened) and *Inferential Statistics* (predicting populations).
3. **Define and compute** core measures of central tendency in Excel: **Mean** (`AVERAGE`), **Median** (`MEDIAN`), and **Mode** (`MODE.SNGL`).
4. **Explain why** different measures of central tendency can tell different stories when extreme values (outliers) exist.
5. **Compute and interpret** measures of spread and range in Excel: **Minimum** (`MIN`), **Maximum** (`MAX`), and **Range** (`MAX - MIN`).
6. **Interpret** statistical results in simple business/analytics language rather than repeating raw numbers.
7. **Navigate and analyze** large datasets (up to 1,000,000 rows) efficiently in Excel without software lag.
8. **Avoid relying on a single statistical metric** when evaluating real-world data.

---

## ⏱️ Course Schedule (90 Minutes)

| Time | Module | Focus Area | Activity Type |
|---|---|---|---|
| **00:00 - 00:10** (10m) | **Part 1: Introduction to Statistics** | Why analysts need statistics; raw data to insights | Interactive Lecture |
| **00:10 - 00:20** (10m) | **Part 2: Types of Statistics** | Descriptive vs. Inferential Statistics | Conceptual Discussion |
| **00:20 - 00:40** (20m) | **Part 3: Central Tendency** | Mean (`AVERAGE`), Median (`MEDIAN`), Mode (`MODE.SNGL`) | Concept + Live Excel Demo |
| **00:40 - 00:55** (15m) | **Part 4: Spread & Range** | Min (`MIN`), Max (`MAX`), Range (`MAX - MIN`) | Excel Demo + Sample Walkthrough |
| **00:55 - 01:20** (25m) | **Part 5: Guided Hands-on Session** | Step-by-step dataset analysis in Excel | Hands-on Student Practice |
| **01:20 - 01:30** (10m) | **Part 6: Challenge & Wrap-up** | 4 Challenge Questions, Recap & Q&A | Quiz & Wrap-up |

---

## 📊 Dataset Overview

The practical workshop utilizes the **Global Health Statistics** dataset (`1,000,000` records across `22` health & socioeconomic variables).

### Key Variables Analyzed:
- **`Average Treatment Cost (USD)`**: Continuous financial metric ($100 to $50,000).
- **`Mortality Rate (%)`**: Health outcome rate (0.10% to 10.00%).
- **`Recovery Rate (%)`**: Patient recovery percentage (50.00% to 99.00%).
- **`Population Affected`**: Outbreak volume metric (1,000 to 1,000,000).
- **`Disease Category`**: Categorical grouping (Metabolic, Viral, Respiratory, etc.).
- **`Doctors per 1000`**: Healthcare staffing density ratio (0.50 to 5.00).

> 💡 *Note: A lightweight 100-row sample dataset [`exercises/sample_health_data.csv`](exercises/sample_health_data.csv) is provided in this repository for instant testing.*

---

## 💡 Quick Statistics Cheat Sheet

| Statistic | What It Tells Us | Excel Function | When to Use It |
|---|---|---|---|
| **Mean** | Arithmetic average | `=AVERAGE(range)` | Symmetric data without severe outliers |
| **Median** | Middle 50th percentile | `=MEDIAN(range)` | Skewed data or data with extreme values |
| **Mode** | Most frequent value | `=MODE.SNGL(range)` | Popular categories or discrete rates |
| **Min / Max** | Lowest and highest values | `=MIN()` / `=MAX()` | Finding lower floor & upper ceiling |
| **Range** | Total spread (Max − Min) | `=MAX() - MIN()` | Measuring overall data variability |

---

## 👨‍🏫 Instructor Details & Author

**Instructor:** Ahmed Muhammed  
**Role:** Data Analyst & Educator  
**GitHub Profile:** [@ahmed-muhammed80](https://github.com/ahmed-muhammed80)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and share for educational purposes.
