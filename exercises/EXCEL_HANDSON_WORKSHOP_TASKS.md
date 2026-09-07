# Guided Hands-on Excel Workshop Exercises

**Duration:** 25 Minutes  
**Tool:** Microsoft Excel  
**Dataset:** `Global Health Statistics.csv` (or `sample_health_data.csv`)

---

## 🛠️ Instructions for Students

Open `Global Health Statistics.csv` in Excel. Complete the following 6 practical tasks by entering Excel formulas into summary cells.

For every task, record:
1. The **Excel Formula** entered.
2. The **Calculated Output**.
3. A **1-sentence Plain-English Interpretation**.

---

### Task 1: Calculate Mean Prevalence Rate (%)
- **Column:** Column E (`Prevalence Rate (%)`)
- **Excel Formula:** `=AVERAGE(E:E)`
- **Expected Output:** `10.05%`
- **Interpretation:** Across 1,000,000 health records, global disease prevalence rates center around 10.05%.
- **Why It Matters:** Gives global health organizations a baseline figure for disease prevalence.

---

### Task 2: Calculate Median Population Affected
- **Column:** Column J (`Population Affected`)
- **Excel Formula:** `=MEDIAN(J:J)`
- **Expected Output:** `501,041`
- **Interpretation:** Exactly 50% of outbreaks affect fewer than 501,041 people, and 50% affect more.
- **Why It Matters:** Helps emergency response teams understand typical outbreak sizes without being skewed by massive outbreaks.

---

### Task 3: Find Mode of Doctors per 1000
- **Column:** Column L (`Doctors per 1000`)
- **Excel Formula:** `=MODE.SNGL(L:L)`
- **Expected Output:** `2.47`
- **Interpretation:** The single most common staffing level is 2.47 doctors per 1,000 people.
- **Why It Matters:** Identifies the most common hospital staffing ratio globally.

---

### Task 4: Find Minimum & Maximum Healthcare Access (%)
- **Column:** Column K (`Healthcare Access (%)`)
- **Excel Formulas:**
  - Minimum: `=MIN(K:K)` -> `50.00%`
  - Maximum: `=MAX(K:K)` -> `100.00%`
- **Interpretation:** Healthcare coverage spans from a low floor of 50.00% to a ceiling of 100.00%.
- **Why It Matters:** Highlights healthcare access inequality between underdeveloped and developed regions.

---

### Task 5: Compute Range of Per Capita Income (USD)
- **Column:** Column T (`Per Capita Income (USD)`)
- **Excel Formula:** `=MAX(T:T) - MIN(T:T)`
- **Expected Output:** `$99,500.00`
- **Interpretation:** There is a total income spread of $99,500.00 between the lowest ($500) and highest ($100,000) income regions.
- **Why It Matters:** Demonstrates severe socioeconomic disparity impacting healthcare affordability.

---

### Task 6: Compare Mean vs Median Treatment Cost (10-Row Sample)
- **Column:** Rows 2 to 11 of Column O (`Average Treatment Cost (USD)`)
- **Excel Formulas:**
  - Mean: `=AVERAGE(O2:O11)` -> `$19,693.20`
  - Median: `=MEDIAN(O2:O11)` -> `$15,661.50`
- **Interpretation:** The mean cost is over $4,000 higher than the median because two expensive treatments ($47,851 and $42,671) pull the mean upward.
- **Why It Matters:** Demonstrates why analysts should use median when describing typical costs to patients or clients.
