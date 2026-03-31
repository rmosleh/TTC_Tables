# TTC Supplementary Tables and Materials

## Overview
This repository contains supplementary materials supporting the study:

**"Modeling Infection Transmission in Subway Systems: A Case Study of the Toronto Transit Commission (TTC)"**

The repository provides detailed tables of estimated model parameters, confidence intervals, and additional results used in the calibration and analysis of a mobility-driven infection transmission model.

📄 Direct access to the supplementary document:  
[TTC_Tables.pdf](./TTC_Tables.pdf)

---

## Repository Contents

This repository includes:

- **TTC_Tables.pdf**  
  A comprehensive collection of supplementary tables containing:
  - Estimated model parameters  
  - 95% confidence intervals  
  - Mobility parameters (inflow and outflow rates)  
  - Transmission parameters for transit hubs and communities  
  - Cluster-specific estimates across multiple time intervals  

---

## Time Segmentation

The analysis is based on the daily operation of the TTC subway system and is divided into four time periods:

- **Morning rush:** 6:00 AM – 9:00 AM  
- **Midday off-peak:** 9:00 AM – 3:00 PM  
- **Afternoon rush:** 3:00 PM – 7:00 PM  
- **Evening off-peak:** 7:00 PM – 2:00 AM (next day)  

---

## Methodological Summary

The results reported in the supplementary tables are obtained using:

- A **deterministic SEIR model** coupled with mobility-driven encounter dynamics  
- A **neighborhood-based clustering approach**, where 70 TTC subway stations are grouped into 8 clusters based on ward structure and connectivity  
- A distinction between:
  - **Transit hubs** (stations and interchanges)  
  - **Residential communities** (associated neighborhood regions)  
- **Least-squares calibration** using MATLAB (`fminsearch`, Optimization Toolbox)  
- Real-world **TTC ridership data** from a representative business day (November 2023)  

---


