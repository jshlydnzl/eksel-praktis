# 🧹 Excel Cleaning Practices

This directory is dedicated to **Phase 1: Data Cleaning and Structuring**.

Before data can be visualized, it must be robustly engineered. The challenges in this folder focus purely on transforming messy, raw datasets into pristine analytical tables using strict Data Engineering principles.

## Core Mechanics Practiced Here
*   **Handling Nulls & Ghosts:** Building robust `=IF()` and `=IFERROR()` logic gates to trap blanks and missing data.
*   **Text & String Parsing:** Using `=TRIM()`, `TEXTSPLIT`, `LEFT/RIGHT`, and Flash Fill to fix invisible spaces, trapped text, and concatenated metadata.
*   **Data Types:** Un-trapping numbers formatted as text, handling currency symbols, and fixing date-to-text formatting traps.
*   **Hunting Anomalies:** Utilizing Conditional Formatting and `COUNTIFS` to detect exact duplicate records.

Each folder contains raw dirty data sets and the final cleaned Excel workbooks built strictly on the **Clean_Data** tab architecture.
