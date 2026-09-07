# Master Instructor Facilitation Guide: Statistics for Data Analysis using Excel

**Course Title:** Statistics for Data Analysis using Microsoft Excel  
**Duration:** 1 Hour 30 Minutes (90 Minutes)  
**Target Audience:** Beginners in Data Analysis & Business Intelligence  
**Dataset:** `Global Health Statistics.csv` (1,000,000 Rows | 22 Columns)

---

## 1. Class Overview & Facilitation Strategy

This guide is designed for an instructor facilitating a **1-hour 30-minute interactive session**. The objective is to teach descriptive statistics through practical Excel data analysis.

### Core Philosophy:
* **Focus on Application & Interpretation:** Avoid dry mathematical proofs. Teach students how Excel formulas calculate metrics and how to interpret outputs into plain-English business language.
* **Keep it Interactive:** Use the 8-10 scripted instructor questions throughout the presentation to engage students.
* **Manage Large Data Smoothly:** Ensure students understand whole-column references (`=AVERAGE(O:O)`) or use the 100-row sample tab (`exercises/sample_health_data.csv`) to prevent Excel software lag.

---

## 2. 90-Minute Agenda Breakdown

| Time | Section | Instructor Script & Activity |
|---|---|---|
| **00:00 - 00:10** | **Part 1: Intro to Statistics** | Define statistics as the art of turning raw data into stories. Show 1M rows in Excel. |
| **00:10 - 00:20** | **Part 2: Types of Statistics** | Discuss Descriptive vs Inferential Statistics. Use the cookie batch analogy. |
| **00:30 - 00:40** | **Part 3: Central Tendency** | Teach Mean (`AVERAGE`), Median (`MEDIAN`), Mode (`MODE.SNGL`). Walk through 10-row sample skewness. |
| **00:40 - 00:55** | **Part 4: Spread & Range** | Demonstrate Min (`MIN`), Max (`MAX`), and Range (`MAX - MIN`). Explain why average alone is dangerous. |
| **00:55 - 01:20** | **Part 5: Guided Hands-on** | Guide students through 6 Excel tasks on the Global Health dataset. |
| **01:20 - 01:30** | **Part 6: Challenge & Wrap-up** | Run 4 challenge questions, reveal Answer Key, review Cheat Sheet & Golden Rules. |

---

## 3. Detailed Part-by-Part Teaching Notes

### PART 1: Introduction to Statistics (10 Mins)
* **What to Say:** *"If you look at 1,000,000 rows of hospital bills, you'll feel overwhelmed. Statistics gives us a magnifying glass to instantly summarize the main story."*
* **Excel Demo:** Open Excel, scroll down 50 rows, ask if anyone can spot the average treatment cost visually.

### PART 2: Types of Statistics (10 Mins)
* **What to Say:** *"Descriptive statistics describes the exact data in front of you. Inferential statistics uses a sample to guess what a larger population looks like."*
* **Analogy:** Weighing all 100 cookies in a batch = Descriptive. Tasting 3 cookies to guess the batch taste = Inferential.

### PART 3: Central Tendency (20 Mins)
* **Mean (`AVERAGE`):** Sum / Count. Show `=AVERAGE(O:O)` -> `$25,010.31`. Explain sensitivity to outliers.
* **Median (`MEDIAN`):** Middle value (50th percentile). Show `=MEDIAN(O:O)` -> `$24,980.00`. Explain why median is safer for skewed data.
* **Mode (`MODE.SNGL`):** Most frequent value. Show `=MODE.SNGL(G:G)` -> `6.54%` mortality rate.
* **Skewness Story:** Walk through the 10-row cost sample: Mean = `$19,693.20` vs Median = `$15,661.50`. Show how two high-cost procedures ($47k and $42k) pull the mean up by over $4,000!

### PART 4: Spread & Range (15 Mins)
* **Minimum (`MIN`):** Smallest value `=MIN(Q:Q)` -> `50.00%` recovery.
* **Maximum (`MAX`):** Largest value `=MAX(Q:Q)` -> `99.00%` recovery.
* **Range:** `=MAX(Q:Q) - MIN(Q:Q)` -> `49.00%` spread.
* **Key Lesson:** Two hospitals can have the exact same average recovery rate, but a hospital with a smaller range is far more consistent!

---

## 4. Troubleshooting Common Beginner Errors

| Error | Root Cause | Fix / Instructor Action |
|---|---|---|
| `#VALUE!` | Text character inside numerical range | Select only numerical ranges in formula. |
| `#NAME?` | Misspelled formula name (e.g. `=AVERGAE()`) | Correct spelling to standard Excel formula (`AVERAGE`). |
| Excel Freezing | User clicked and dragged mouse down 1M rows | Teach keyboard shortcut `Ctrl+Shift+↓` or whole-column `O:O`. |
| `0.05` instead of `5%` | Default number formatting set to General | Change formatting to **Percentage (%)** on Home Tab. |
