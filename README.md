# 📖 Quran Surah and Verse Analysis

This project explores a fascinating numerical pattern within the **Quran** — examining how each Surah’s serial number and verse count combine into even or odd totals.

## 🧩 Overview

- **Total Surahs:** 114  
- **Total Verses:** 6236  

Each Surah is represented as a tuple `(surah_number, number_of_verses)`.

The Python script calculates:  
- Whether `(surah_number + number_of_verses)` is even or odd  
- The total count and sum of even vs odd results  
- The total sum of all Surah serials  

## 📊 Results

| Metric | Result | Examples |
|--------|--------:|--------|
| Count of even (serial + verses) sums | 57 | `Count` (2+286=288), (4+176=180), (16+128=144) |
| Count of odd (serial + verses) sums | 57 | `Count` (3+200=203), (5+120=125), (33+73=106) |
| Sum of [serial + verses] in even Surahs | 6236 | `Add` (2+286)+(4+176)+... |
| Sum of [serial + verses] in odd Surahs | 6555 | `Add` (3+200)+(5+120)+... |
| Total verses in Quran | 6236 | Fixed total |
| Sum of all Surah serials | 6555 | `Add all serial numbers`  1+2+3+.....+114 |

## 🧠 Insights

- The Quran has **57 even** and **57 odd** `(serial + verse)` sums — perfectly balanced.  
- The **sum of all Surah serials (6555)** equals the total of both even and odd sums combined divided by two.  
- These patterns have been a topic of mathematical interest in Quranic studies.
