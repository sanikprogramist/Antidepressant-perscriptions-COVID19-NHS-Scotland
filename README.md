# **Full Written Report**
➡️ **https://sanikprogramist.github.io/Antidepressant-perscriptions-COVID19-NHS-Scotland/**

---

# Trends in Antidepressant Prescription During the COVID-19 Pandemic  
**Author:** *[Your Name]*  
**Date:** 11/06/2022  

This repository contains the data preparation, visualisations, and statistical analyses used to investigate whether the COVID-19 pandemic influenced antidepressant prescription rates across Scotland. The project combines publicly available NHS Scotland datasets, tidyverse-based wrangling, and ggplot2-driven visualisations to explore changes before, during, and after the onset of COVID-19.

---

## **Project Overview**

The COVID-19 pandemic was a major societal stressor and has been associated with a substantial increase in the prevalence of anxiety and depression worldwide. This study evaluates whether these trends translated into increased prescribing of antidepressants across Scotland, both in the short term (pandemic onset in March 2020) and in the longer aftermath.

Core research questions:

1. **Did the pandemic influence overall antidepressant prescription rates?**
2. **Did those effects vary between NHS Health Boards?**
3. **Is socioeconomic deprivation associated with changes in prescription rates?**
4. **Did COVID-19 alter the long-term trajectory of antidepressant prescribing?**

---

## 🔍 **Analysis Breakdown**

### **1. Antidepressant Prescription Trends Across Scotland**
- **Objective:** Identify changes in item quantities and ingredient costs around March 2020.
- **Key finding:** Both prescription volume and gross cost peaked sharply at the pandemic onset.
- **Possible explanation:** Pandemic-driven anxiety, precautionary medication stockpiling, and global API shortages.

### **2. Regional Variation Across NHS Health Boards**
- **Method:** Normalised prescriptions by population, analysed per-board trends.
- **Finding:** All boards saw increases, though magnitude differed by region.

### **3. Socioeconomic Deprivation and Prescription Change**
- **Data sources:** Scottish Index of Multiple Deprivation (SIMD) and GP demographics.
- **Result:** Contrary to expectation, no strong correlation between deprivation and prescription increase was found.

### **4. Long-Term Effects on Prescription Rates**
- **Approach:** Compared monthly growth rates in 2019 vs. 2021 using linear models.
- **Result:** Growth rates increased in nearly every Health Board, suggesting a persistent post-COVID impact.

---

## **Technologies & Libraries Used**

- **R**, along with:
  - `tidyverse`, `lubridate`, `patchwork`, `ggpubr`, `rslang`, `gt`, `broom`, `pals`, `scales`, `here`

These enabled data wrangling, cost normalisation, modelling, and layered graphical output.

---

## **Citation & References**
This project incorporates publicly available NHS datasets, WHO statistics, and published literature on COVID-19, pharmaceutical shortages, and mental health patterns.

For a full bibliography and complete write-up, **visit the report link at the top of this README**.

---

## **Conclusion**

The COVID-19 pandemic significantly impacted antidepressant prescribing in Scotland—both immediately and in the longer term. Although the pandemic did not appear to affect deprived regions disproportionately at onset, the sustained growth in prescriptions across nearly all NHS Health Boards points toward continuing mental-health consequences beyond the crisis itself.

---

## **Contact**

If you have questions, feedback, or suggestions for extensions, feel free to open an issue or contact the author.

---

**Thanks for exploring this repository!**
