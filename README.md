# Participation Patterns in Swedish Study Association Activities

## Overview
This project analyzes participation patterns in Swedish study association activities using official data from Statistics Sweden (SCB).

The objective is to identify **structural patterns in participation behavior** across age, gender, and education, and to assess whether these patterns were disrupted by the COVID-19 pandemic.

The analysis is designed to reflect how real-world statistical data—containing multiple aggregation levels and overlapping categories—can be transformed into **clear, interpretable insights** through careful filtering and structured analysis.

---

## Executive Summary

The analysis reveals a **clear and stable life-cycle pattern** in participation:

- Participation is highest in early adulthood (20–24)
- It drops sharply during the transition into working life (25–29)
- It remains moderate through mid-life
- It rises again around retirement age (65–74)
- It declines in the oldest age groups

Additional key findings:

- Women consistently participate more than men across all age groups  
- Higher education is strongly associated with higher participation  
- The COVID-19 shock significantly reduced participation levels, but **did not alter the underlying structure**

Overall, participation appears to be driven by **life-stage transitions and socio-demographic factors**, rather than short-term external shocks.

---

## Analytical Focus

The project addresses four core questions:

- How does participation vary across age groups?
- Are there systematic differences between men and women?
- How does participation differ by education level?
- Did the COVID-19 shock in 2021 change the underlying structure?

---

## Data and Method

### Data Source
- Statistics Sweden (SCB)
- National-level aggregated data (2020–2024)

### Key Data Characteristics
The dataset is a **multi-dimensional statistical structure (data cube)** flattened into tabular form. It includes:

- Both **detailed and aggregated categories** (e.g., age groups and “all ages”)
- Multiple hierarchical dimensions (age, gender, education, region, organization)
- Participation measured as **events**, not unique individuals

### Methodological Approach
- Careful filtering to ensure **non-overlapping and comparable groups**
- Aggregation by relevant dimensions (age, gender, education)
- Use of descriptive statistics and visualization
- Robustness checks (e.g., excluding COVID-affected year)

The analysis is **descriptive by design** and does not attempt to estimate causal relationships.

---

## Key Design Choices

- Participation is measured using **participation events**, not individuals  
  → results reflect **participation intensity**, not participation rates  

- Aggregated categories (e.g., “all ages”) are excluded  
  → prevents **double counting and misleading comparisons**

- Only **non-overlapping age groups** are used  
  → ensures valid comparisons across the life cycle  

- Distribution plots were intentionally excluded  
  → the data is already aggregated, and such plots do not add meaningful insight  

---

## Key Findings

### 1. Life-Cycle Structure
Participation follows a clear and interpretable life-cycle pattern, strongly aligned with major life transitions such as education, work entry, and retirement.

### 2. Early-Adulthood Drop
The largest decline occurs between ages 20–24 and 25–29 (~42%), suggesting a structural break associated with entry into the labor market and family formation.

### 3. Gender Differences
Women generate approximately **1.7–1.9 times more participation events** than men across the observed period.  
The difference is persistent and structurally stable.

### 4. Education Gradient
Higher educational attainment is strongly associated with higher participation levels across most adult age groups.

### 5. COVID-19 Impact
Participation declined across all groups in 2021, with larger relative declines among older individuals.  
However, the **overall life-cycle structure remained intact**, indicating structural stability.

---

## Why No Statistical Model is Fitted

Although it is possible to fit statistical models (e.g., regression or polynomial fits), this approach is intentionally not pursued.

The observed patterns reflect **distinct life stages**, not a single continuous process.  
Fitting a model would primarily reproduce the observed shape without adding meaningful explanatory value.

More flexible models would risk **overfitting** and incorrectly suggesting a smooth, continuous relationship.

For this reason, the analysis focuses on:
- structural interpretation  
- descriptive clarity  
- robustness of observed patterns  

---

## Limitations

- The data measures **participation events**, not unique individuals  
- The analysis is **cross-sectional**, not longitudinal  
- Results are **descriptive**, not causal  
- Education is difficult to interpret for younger age groups  
- The dataset includes hierarchical aggregation, requiring careful filtering  

---

## Why This Matters

The findings have direct relevance for:

- **Cultural policy and public funding**
- **Social inclusion and accessibility**
- **Targeting of underrepresented groups**
- **Understanding participation inequalities**

Key implications:

- Ages 25–29 represent a **critical disengagement point**
- Older adults show strong participation, highlighting the role of **lifelong learning**
- Gender and education differences suggest **unequal access or engagement**
- Participation is shaped by **structural factors**, not only short-term conditions

---

## Tools Used

- Python  
- pandas  
- numpy  
- matplotlib  
- Jupyter Notebook  

---

## Repository Structure

- `notebook.ipynb` — full analysis  
- `README.md` — project overview  

---

## About Me

I have a background in statistics and am currently developing my skills in data analysis.

My focus is on transforming complex, real-world data into **clear, structured, and interpretable insights**, with particular interest in societal and policy-relevant analysis.

---

## Final Note

This project demonstrates how complex, multi-dimensional public data can be transformed into a structured analytical narrative.

The emphasis is not on advanced modeling, but on:
- correct data handling  
- analytical reasoning  
- clear communication of insights  
