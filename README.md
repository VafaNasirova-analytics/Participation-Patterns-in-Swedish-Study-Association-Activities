# Participation-Patterns-in-Swedish-Study-Association-Activities

This project analyzes participation patterns in Swedish study association activities using official statistics from Statistics Sweden (SCB).

The goal is to identify robust structural patterns in participation across age, gender, and education, and to examine whether the COVID-19 shock in 2021 altered these patterns.

---

## Key Questions

- How does participation vary across age groups?
- How do participation patterns differ by gender and education level?
- Did the COVID-19 shock in 2021 change the underlying structure of participation?

---

## Main Insight

Participation follows a clear life-cycle pattern:

- High in early adulthood  
- Declines during the transition into work and family formation  
- Rises again around retirement age  
- Declines in the oldest age groups  

This pattern remains stable even after accounting for the COVID-19 disruption.

---

## Key Findings

- Participation exhibits a strong life-cycle structure
- The sharpest decline occurs in ages 25–29
- Women consistently show higher participation levels than men
- Participation is systematically higher among individuals with longer post-secondary education
- The COVID-19 shock affected participation levels, but not the underlying structure

---

## Methodology

The analysis is descriptive and focuses on identifying structural patterns rather than causal effects.

Key steps include:

- Careful filtering of overlapping categories (age, education, region)
- Use of non-overlapping age groups for comparability
- Separation of aggregate and detailed categories
- Robustness checks excluding the COVID-19 year (2021)
- Use of coefficient of variation to assess stability over time

---

## Data

Source: Statistics Sweden (SCB)

The dataset contains participation events (not unique individuals), meaning that individuals may be counted multiple times.

Variables include:

- Age group
- Gender
- Education level
- Year
- Participation counts

---

## Tools and Technologies

- Python
- pandas
- NumPy
- Matplotlib

---

## Limitations

- Measures participation events, not individuals
- Cross-sectional analysis (not longitudinal)
- Descriptive (no causal inference)
- Potential differences in participation context across age groups

---

## Why This Matters

Understanding participation patterns is important for:

- Cultural policy and public funding
- Identifying underrepresented groups
- Evaluating structural inequalities in access to educational and cultural activities

---

## Project Structure

- `Participation Patterns in Swedish Study Association Activities.ipynb` – main analysis notebook

---

## Author

Vafa Nasirova  
BSc in Statistics  
