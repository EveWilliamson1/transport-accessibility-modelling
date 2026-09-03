# Public Transport Accessibility & Commuting Inequality 🚌📍

**Final-Year Project — BSc Financial Mathematics, Cardiff University**

**Grade: 94% | Ranked 2nd in School of Mathematics | 1st in BSc Financial Mathematics**

This dissertation develops a mathematical **generalised cost accessibility index** to quantify the burden of commuting by public transport to Cardiff University's Cathays and Heath Park campuses.

The project combines **transport modelling, GIS, statistical analysis and real-world staff travel data** to investigate how accessibility varies across Cardiff and whether poorer public transport accessibility is associated with deprivation and greater reliance on private cars.

## Project Overview

Traditional accessibility measures such as nearby bus stop counts or service frequency do not necessarily represent how difficult a journey actually is.

To address this, I developed a destination-specific accessibility measure incorporating multiple components of a public transport journey, including:

- Walking time
- In-vehicle travel time
- Waiting and interchange time
- Public transport fares
- Temporal variability
- Penalties for inaccessible areas

Accessibility was modelled at **Lower Super Output Area (LSOA)** level across Cardiff, allowing commuting burden to be compared spatially and between university campuses.

## Data & Methodology

The analysis integrates several real-world datasets, including:

- **Cardiff University Staff Travel Survey (2024)**
- **Welsh Index of Multiple Deprivation (WIMD 2019)**
- **Cardiff Bus GTFS network data**
- **Google Routes API journey data**
- Geographic and public transport network data

The project involved:

- Cleaning and integrating staff travel and spatial datasets
- GIS-based analysis of staff residential locations and deprivation
- Public transport network and origin-to-destination route modelling
- Construction of a composite generalised cost accessibility index
- Spatial comparison of accessibility across Cardiff
- Statistical modelling of accessibility and driving behaviour
- Comparison against simpler accessibility measures
- Sensitivity and robustness analysis

## Key Findings

- Public transport accessibility varies substantially across Cardiff.
- **Heath Park has higher generalised accessibility costs than Cathays**, indicating a greater public transport burden for many journeys.
- Higher accessibility costs are associated with **greater single-occupancy car driving frequency**, although this relationship weakens after controlling for deprivation.
- Cardiff University staff living within Cardiff are disproportionately concentrated in **less deprived areas**, particularly WIMD deciles 8–10.
- The generalised cost index showed a stronger relationship with observed commuting behaviour than simpler measures such as **bus stop counts and service departures**.
- The results suggest that sustainable transport interventions should focus on reducing the **actual journey burden**, rather than simply increasing nearby transport provision.

## Methodological Contribution

A key contribution of the project is the conversion of heterogeneous journey characteristics into a **single interpretable accessibility cost measure**.

Rather than measuring public transport availability alone, the framework evaluates the complete origin-to-destination commuting burden and connects this with observed travel behaviour and socioeconomic conditions.

This provides a framework for identifying spatial inequalities in transport accessibility and evaluating where targeted transport interventions may be most effective.

## Tools & Techniques

**R / Statistical Analysis**  
Regression modelling • hypothesis testing • sensitivity analysis • data visualisation

**Python / Transport Modelling**  
API processing • route modelling • data cleaning and integration

**GIS & Spatial Analysis**  
LSOA-level analysis • spatial joins • accessibility mapping • deprivation analysis

**Transport Data**  
GTFS • Google Routes API • origin-to-destination modelling • generalised cost modelling

## Research Questions

1. How can public transport accessibility to Cardiff University campuses be quantified using a route-based generalised cost index?
2. How does accessibility vary spatially across Cardiff and between Cathays and Heath Park?
3. What is the relationship between accessibility, area-level deprivation and staff commuting behaviour?
4. Does a generalised accessibility cost index provide more insight into commuting burden than simpler measures such as bus stop counts and departures?

## Project Files

📄 **[Read the full dissertation](./Modelling_Public_Transport_Accessibility_and_Commuting.pdf)**

> **Academic achievement:** This project received **94% and was ranked 1st in the cohort** within the Cardiff University School of Mathematics.

---

**Cardiff University | BSc Financial Mathematics | 2026**
