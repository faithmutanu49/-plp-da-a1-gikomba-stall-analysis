# -plp-da-a1-gikomba-stall-analysis
# Gikomba Stall Analysis

**Analyst:** [FAITH MUTANU MBITHI]
**Cohort:** [1 MILLION DEVS]

## Business problem

Wanjiku runs a fresh-produce stall at Gikomba Market. For two weeks she has recorded her daily sales in a notebook and kept a rough record of her stock. She wants to know how her business is doing, whether it is growing, which products she should restock, and where she should focus her effort. This project answers those questions using only core Python (no pandas or NumPy): summary statistics, week-on-week growth, day classification, weekday versus weekend performance, a restock list and gross margins by product.

## How to run

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1NQ84txRXeupYFzzs9P9ub6pNBncTz8Ch?usp=sharing)

Click the badge, then choose **Runtime → Run all**. No installs are needed.

## Top three findings

1. **The business is growing.** Sales rose **10.7%** week-on-week, from KES 22,050 in week 1 to KES 24,400 in week 2 (total KES 46,450 over 14 days).
2. **Weekends drive the business.** Saturday and Sunday average **KES 4,900** a day versus **KES 2,685** on weekdays, which is **82.5% higher**. All 4 "Strong" days were weekend days, and all 6 "Weak" days were weekdays.
3. **Two products need restocking now.** Tomatoes (18 kg against a 25 kg level) and Sukuma (9 kg against a 15 kg level) are below their reorder levels. Avocado has the best margin at **42.9%**, while Onions have the lowest at **30.0%**.

## Files

- `wanjiku_stall_analysis.ipynb`: the full analysis, Tasks 1-7, with the printed Stall Performance Report and recommendations.
- `README.md`: this file.
