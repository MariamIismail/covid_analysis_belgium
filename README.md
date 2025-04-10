# Theoretical modelling the early phase of the Belgian COVID-19 epidemic using compartmental model and studying the factors associated with the hospitalization dynamics

**Author**: Mariam ISMAIL  
**Date**: 2025-04-09

## Introduction

The COVID-19 pandemic led to the generation of an unprecedented volume of global data. This project focuses on i) developing a theoretical model using an extended SIR model and ii) studying factors associated with the number of new hospitalization patients during the early phase of the Belgian COVID-19 epidemic.

## Data

The dataset used in this study is the COVID-19 Open Dataset (COD), available at goo.gle/covid-19-open-data. This dataset provides comprehensive time series data from multiple sources and includes two main categories of information. First, it contains epidemiological data such as the number of new hospitalized patients, confirmed cases, deaths, and recoveries. Second, it includes time series data on potentially relevant predictors of new hospitalizations, such as population mobility patterns and weather conditions. This combination allows for an analysis of the factors associated with the hospitalization dynamics. For this study, data from Belgium was selected, focusing on the early phase of the epidemic between March 15, 2020, and June 29, 2020.

---

## Repository Structure


- **`data/`**: Contains cleaned CSV datasets from the [Google COVID-19 Open Data repository](https://goo.gle/covid-19-open-data), filtered for Belgium.
- **`analysis.Rmd`**: R Markdown file containing the analysis analyses coded in R langauge.
- **`README.md`**: This file.

---

