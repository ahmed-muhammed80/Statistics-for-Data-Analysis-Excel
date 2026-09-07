# Statistics for Data Analysis — Excel Cheat Sheet

A quick-reference sheet for beginner data analysts learning descriptive statistics in Microsoft Excel.

---

## 📊 Core Descriptive Statistics Summary Table

| Statistic | What It Measures | Excel Function | Example Formula | When to Use It |
|---|---|---|---|---|
| **Mean** | The arithmetic average of all numbers. | `=AVERAGE(range)` | `=AVERAGE(O:O)` | When numerical data is evenly distributed without extreme outliers. |
| **Median** | The exact middle value (50th percentile) when data is ordered. | `=MEDIAN(range)` | `=MEDIAN(O:O)` | When data contains extreme high or low values (skewed data). |
| **Mode** | The most frequently occurring value in the dataset. | `=MODE.SNGL(range)` | `=MODE.SNGL(G:G)` | When looking for the most common category, rating, or discrete value. |
| **Minimum** | The smallest value in the column. | `=MIN(range)` | `=MIN(Q:Q)` | To find the worst-case floor or minimum benchmark. |
| **Maximum** | The largest value in the column. | `=MAX(range)` | `=MAX(Q:Q)` | To find the best-case ceiling or maximum benchmark. |
| **Range** | The total spread between max and min. | `=MAX(range) - MIN(range)` | `=MAX(Q:Q) - MIN(Q:Q)` | To measure overall variability and consistency of data. |

---

## ⌨️ Essential Excel Shortcuts for Big Datasets

- **Select Down to Last Row:** `Ctrl + Shift + ↓` (Windows) \| `Cmd + Shift + ↓` (Mac)
- **Select Whole Column:** Click Column Header letter (e.g. `O:O`)
- **Format Number as Currency ($):** `Ctrl + Shift + 4` (`$`)
- **Format Number as Percentage (%):** `Ctrl + Shift + 5` (`%`)

---

## 💡 The 5 Golden Rules of Data Interpretation

1. **Never use just one metric:** Combine Mean, Median, Min, and Max for a complete picture.
2. **Watch out for outliers:** If Mean and Median are very different, the Mean is skewed!
3. **Speak business language:** Translate `$25,010` into *"Treatment costs typically center around $25,010."*
4. **Descriptive stats only describes what you measured:** Avoid making wild assumptions beyond your dataset.
5. **You are the analyst, Excel is just the tool:** Always ask *"So what does this number mean?"* after every formula.
