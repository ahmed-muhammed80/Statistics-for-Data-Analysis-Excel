# Lesson Slides Outline (Markdown Export)

This document contains the complete Markdown text for all 16 slides. You can copy and paste this content directly into **Marp**, **Google Slides**, **PowerPoint**, or **Keynote**.

---

## SLIDE 1: Title Slide
# Statistics for Data Analysis
### A Practical, Beginner-Friendly Guide Using Microsoft Excel

* **Target Audience:** Beginners in Data Analysis
* **Duration:** 1 Hour 30 Minutes (90 Minutes)
* **Dataset:** Global Health Statistics (1,000,000 Records)

> *"Statistics is not about memorizing complex equations. It is your tool for turning raw spreadsheets into clear human stories."*

---

## SLIDE 2: Agenda
# 90-Minute Lesson Agenda

| Time | Module | Core Focus |
|---|---|---|
| **10 min** | **Part 1: Introduction** | Why analysts need statistics; raw data to insights |
| **10 min** | **Part 2: Types of Statistics** | Descriptive vs. Inferential Statistics |
| **20 min** | **Part 3: Central Tendency** | Mean (`AVERAGE`), Median (`MEDIAN`), Mode (`MODE.SNGL`) |
| **15 min** | **Part 4: Spread & Range** | Min (`MIN`), Max (`MAX`), Range (`MAX - MIN`) |
| **25 min** | **Part 5: Guided Hands-on** | Step-by-step Excel workshop on dataset |
| **10 min** | **Part 6: Challenge & Wrap-up** | Student Challenge, Answer Key & 5 Golden Rules |

---

## SLIDE 3: Dataset Overview
# Our Dataset: Global Health Statistics

* **File:** `Global Health Statistics.csv` (1,000,000 Rows \| 22 Columns)

### Key Columns:
1. `Average Treatment Cost (USD)` — Financial metric ($100 to $50,000)
2. `Mortality Rate (%)` — Health outcome rate (0.10% to 10.00%)
3. `Recovery Rate (%)` — Patient outcome rate (50.00% to 99.00%)
4. `Population Affected` — Outbreak volume (1,000 to 1,000,000)
5. `Disease Category` — Categorical text (Metabolic, Viral, etc.)
6. `Doctors per 1000` — Healthcare staffing density (0.50 to 5.00)

---

## SLIDE 4: Excel Efficiency
# Handling 1,000,000 Rows in Excel

1. **Use Whole-Column References:** Enter `=AVERAGE(O:O)` instead of dragging ranges.
2. **Keyboard Shortcuts:** `Ctrl + Shift + ↓` (Windows) / `Cmd + Shift + ↓` (Mac).
3. **Use a Working Sample Sheet:** Practice live formulas on a 100-row sample tab!

---

## SLIDE 5: Part 1 — Intro to Statistics
# What is Statistics in Data Analysis?

* **Without Statistics:** Looking at 1,000,000 rows line-by-line causes information overload.
* **With Statistics:** Summarizing 1,000,000 rows into 3 clean metrics: Average Cost ($25,010), Median Cost ($24,980), and Range ($49,900) creates an instant executive narrative.

---

## SLIDE 6: Part 2 — Types of Statistics
# Descriptive vs. Inferential Statistics

* **Descriptive Statistics (Our Focus Today):** *"What does our data tell us right now?"* Summarizes and describes the exact dataset measured.
* **Inferential Statistics:** *"What can we infer about the whole world?"* Uses a small sample to make predictions about unseen populations.

---

## SLIDE 7: Part 3A — Central Tendency: Mean
# Central Tendency: The Mean (Average)

* **Concept:** Arithmetic average (Sum divided by Count).
* **Excel Formula:** `=AVERAGE(O:O)`
* **Dataset Output:** `$25,010.31`
* **Interpretation:** Across 1,000,000 health records, treatment costs center around **$25,010.31**.

---

## SLIDE 8: Part 3B — Central Tendency: Median
# Central Tendency: The Median (Middle Value)

* **Concept:** The exact 50th percentile midpoint when sorted smallest to largest.
* **Excel Formula:** `=MEDIAN(O:O)`
* **Dataset Output:** `$24,980.00`
* **Interpretation:** Exactly 50% of treatment costs are below **$24,980.00**, and 50% are above.

---

## SLIDE 9: Part 3C — Central Tendency: Mode
# Central Tendency: The Mode (Most Frequent)

* **Concept:** The most frequently occurring value in a dataset.
* **Excel Formula:** `=MODE.SNGL(G:G)`
* **Dataset Output:** `6.54%`
* **Interpretation:** The single most common mortality rate recorded is **6.54%**.

---

## SLIDE 10: Part 3D — Mean vs. Median Story
# Mean vs. Median: The Skewness Story

### 10-Patient Sample Costs:
`$21,064 | $47,851 | $27,834 | $144 | $8,908 | $42,671 | $15,579 | $15,744 | $7,669 | $9,468`

* **Calculated Mean:** `$19,693.20`
* **Calculated Median:** `$15,661.50`
* **Analyst Verdict:** Two expensive treatments ($47k & $42k) pull the **Mean up by over $4,000**. The **Median** is safer for describing a typical patient!

---

## SLIDE 11: Part 4 — Spread & Range
# Measuring Data Spread & Range

* **Minimum:** `=MIN(Q:Q)` → **50.00%** (Recovery Rate)
* **Maximum:** `=MAX(Q:Q)` → **99.00%** (Recovery Rate)
* **Range:** `=MAX(Q:Q) - MIN(Q:Q)` → **49.00%** spread
* **Interpretation:** Recovery rates span from 50.00% to 99.00%, creating a total spread of 49.00 percentage points.

---

## SLIDE 12: Part 5 — Guided Workshop Tasks
# Hands-on Excel Workshop Tasks

1. **Mean Prevalence Rate (%):** `=AVERAGE(E:E)` → **10.05%**
2. **Median Population Affected:** `=MEDIAN(J:J)` → **501,041**
3. **Mode Doctors per 1000:** `=MODE.SNGL(L:L)` → **2.47**
4. **Min & Max Healthcare Access (%):** `=MIN(K:K)` / `=MAX(K:K)` → **50.00% to 100.00%**
5. **Income Range (USD):** `=MAX(T:T) - MIN(T:T)` → **$99,500.00**

---

## SLIDE 13: Student Challenge
# Student Hands-on Challenge

* **Q1:** What is the average `Mortality Rate (%)` across the dataset?
* **Q2:** What is the median `Recovery Rate (%)`?
* **Q3:** What is the range of `Hospital Beds per 1000` (Column M)?
* **Q4:** For `Average Treatment Cost (USD)`, which is higher: Mean or Median? What does this tell us?

---

## SLIDE 14: Answer Key
# Instructor Answer Key

| Question | Formula | Result | Plain-English Interpretation |
|---|---|---|---|
| **Q1** | `=AVERAGE(G:G)` | **5.05%** | Global mortality rates center around 5.05%. |
| **Q2** | `=MEDIAN(Q:Q)` | **74.47%** | 50% of records show recovery rates above 74.47%. |
| **Q3** | `=MAX(M:M)-MIN(M:M)` | **9.50 beds** | Beds span from 0.50 to 10.00 beds/1k. |
| **Q4** | Mean vs Median | **Mean > Median** | Mean ($25,010) > Median ($24,980) due to high outliers. |

---

## SLIDE 15: Statistics Cheat Sheet
# Statistics Cheat Sheet

| Statistic | What It Tells Us | Excel Function | When to Use It |
|---|---|---|---|
| **Mean** | Arithmetic average | `=AVERAGE(range)` | Symmetric data without outliers |
| **Median** | Middle 50th percentile | `=MEDIAN(range)` | Skewed data or data with outliers |
| **Mode** | Most frequent value | `=MODE.SNGL(range)` | Popular categories or discrete rates |
| **Min / Max** | Smallest / Largest value | `=MIN()` / `=MAX()` | Finding lower floor & upper ceiling |
| **Range** | Total spread (Max − Min) | `=MAX() - MIN()` | Measuring overall consistency |

---

## SLIDE 16: 5 Key Takeaways & Wrap Up
# 5 Golden Rules for Beginner Data Analysts

1. **Never Rely on a Single Metric:** Check Mean, Median, Min, and Max together.
2. **Beware of Outliers:** When data is skewed by extreme numbers, trust the Median!
3. **Speak Plain English:** Translate formulas into clear business narratives.
4. **Know Your Scope:** Descriptive statistics only claims what is in your data records.
5. **You Are the Thinker:** Excel computes numbers instantly, but only YOU interpret what they mean for business!
