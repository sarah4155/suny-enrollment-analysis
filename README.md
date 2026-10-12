# SUNY-Enrollment-Analysis
An exploratory analysis of SUNY enrollment data from 2011 to 2025 using Python, pandas, and matplotlib.

## Questions to Answer
1. How has total SUNY enrollment changed over time?
2. Which types of colleges lost or recovered the most?
3. Which campuses are the largest?
4. Which campuses have lost the most students since 2019?

## Data
Headcount enrollment by student level and student load for SUNY institutions, from NY Open Data (fall 2011 onward). Each row is one campus in one fall term, split into undergraduate and graduate students, full-time and part-time.

## Cleaning
- Converted headcount columns from text with commas to numbers.
- Filled blank cells with 0, since a blank means no students in that group (for example, community colleges have no graduate students).
- Removed sector subtotal and SUNY-wide total rows to avoid double-counting.

## Key findings
- Enrollment was lowest in 2022 at about 364,000 students, down roughly 100,000 from 468,000 in 2011.
- Doctoral Degree Granting Institutions recovered best. They grew about 12% since 2011 and are the only sector above their 2019 level.
- The largest campus in 2025 was Buffalo University, with about 31,700 students.
- 46 of the 61 campuses are still below their 2019 enrollment.

## Tools
Python, pandas, matplotlib, Jupyter Notebook

## Files
- `SUNY_Enrollment_Analysis.ipynb`
- Original CSV data file
