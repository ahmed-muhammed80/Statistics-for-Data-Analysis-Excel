# Student Challenge & Instructor Answer Key

This document contains the student challenge questions presented at the end of the hands-on session, along with exact Excel formulas, calculated outputs, and plain-English interpretations for the instructor.

---

## 📋 Student Challenge Questions

Give students **5 minutes** to solve these 4 questions in Excel using `Global Health Statistics.csv`:

1. **Q1:** What is the average `Mortality Rate (%)` across the dataset?
2. **Q2:** What is the median `Recovery Rate (%)`?
3. **Q3:** What is the range of `Hospital Beds per 1000` (Column M)?
4. **Q4:** For `Average Treatment Cost (USD)`, which metric is higher: Mean or Median? What does this tell us?

---

## 🔑 Detailed Instructor Answer Key

### Q1: What is the average Mortality Rate (%) across the dataset?
* **Column:** Column G (`Mortality Rate (%)`)
* **Excel Formula:** `=AVERAGE(G2:G1000001)` or `=AVERAGE(G:G)`
* **Exact Calculated Output:** **`5.05%`** (or `5.0499%`)
* **Plain-English Interpretation:** Across 1,000,000 recorded health incidents, the global mortality rate typically centers around **5.05%**.
* **Instructor Guidance:** Praise students who format their output cell as a percentage (%) rather than decimal `0.0505`.

---

### Q2: What is the median Recovery Rate (%)?
* **Column:** Column Q (`Recovery Rate (%)`)
* **Excel Formula:** `=MEDIAN(Q2:Q1000001)` or `=MEDIAN(Q:Q)`
* **Exact Calculated Output:** **`74.47%`** (Full dataset) / **`84.23%`** (10-row sample)
* **Plain-English Interpretation:** Exactly 50% of the patient records report a recovery rate higher than **74.47%**, and 50% report lower.
* **Instructor Guidance:** Remind students that median represents the exact 50th percentile mark.

---

### Q3: What is the range of Hospital Beds per 1000 (Column M)?
* **Column:** Column M (`Hospital Beds per 1000`)
* **Excel Formulas:**
  * Maximum: `=MAX(M2:M1000001)` -> `10.00`
  * Minimum: `=MIN(M2:M1000001)` -> `0.50`
  * Range: `=MAX(M2:M1000001) - MIN(M2:M1000001)`
* **Exact Calculated Output:** **`9.50 beds per 1,000 people`**
* **Plain-English Interpretation:** There is a total spread of **9.50 beds per 1,000 people** between the least resourced healthcare region (0.50 beds) and the most resourced (10.00 beds).
* **Instructor Guidance:** Emphasize that range measures total variability across regions.

---

### Q4: For Average Treatment Cost (USD), which metric is higher: Mean or Median? What does this tell us?
* **Column:** Column O (`Average Treatment Cost (USD)`)
* **Exact Values (Full Dataset):**
  * Mean = **`$25,010.31`**
  * Median = **`$24,980.00`** (Mean is **`$30.31`** higher)
* **Exact Values (First 10 Rows Sample):**
  * Mean = **`$19,693.20`**
  * Median = **`$15,661.50`** (Mean is **`$4,031.70`** higher)
* **Instructor Script Explanation:** *"The Mean is higher than the Median. This indicates that high treatment costs (expensive surgeries/treatments) are pulling the average upwards. The Median ($24,980.00) gives a safer, more accurate picture of what a typical patient pays."*
