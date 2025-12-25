[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange.svg)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![License: MIT](https://img.shields.io/badge/Climatic_Analysis-CABAÑUELAS-blue)](CABAÑUELAS)
[![License: MIT](https://img.shields.io/badge/Colombia_Climatic-CABAÑUELAS-green)](Colombia)
[![License: MIT](https://img.shields.io/badge/Climatic_Culture-Perceptions-green)](Culture)


# Cabañuelas´s Analysis

_The scientific assessment of traditional forecasting practices such as Las Cabañuelas lies at the crossroads of ethnometeorology, statistical evaluation, and contemporary climate science. Whereas modern meteorology is grounded in physically based numerical models supported by extensive observing and data-assimilation systems, Las Cabañuelas draws on generational observational experience transmitted through cultural tradition. These practices are often treated with skepticism in scientific settings because they are perceived to lack empirical support, yet comparatively few studies have subjected them to rigorous, out-of-sample statistical validation of predictive skill._

## Cabañuelas-Colombia: data, code, and hindcast evaluation. Early-January weather vs. same-year climate—myth or method? 

This repo contains the data and code behind our paper testing the Cabañuelas hypothesis in Colombia (2000–2024), from exploratory correlations to a strict leave-one-year-out (LOY–O) hindcast with robust baselines and uncertainty.

## Original datasets:

- The data used in this study were obtained from the open data repository of the Instituto de Hidrología, Meteorología y Estudios Ambientales (IDEAM, Colombian Institute of Hydrology, Meteorology, and Environmental Studies). 
- The original datasets were accessed through the Socrata platform at the following URLs:
  - Rainfall: https://dev.socrata.com/foundry/www.datos.gov.co/s54a-sgyg
  - Humidity: https://dev.socrata.com/foundry/www.datos.gov.co/uext-mhny
  - Temperature: https://dev.socrata.com/foundry/www.datos.gov.co/sbwg-7ju4

## Methodology:
**Data processing workflow for merging rainfall, temperature, and humidity datasets.** The process includes data cleaning, correction, feature computation, and final dataset structuring with daily and monthly aggregations.

![Methodology_graph](https://github.com/sierraporta/cabanuelas-analysis/blob/main/Methodology_graph.png)

## Colomia´s Regions:
**Natural Regions of Colombia.** The map shows the five major geographical regions of Colombia—Caribbean, Andean, Pacific, Orinoquía, and Amazon—each with distinct climatic characteristics. These variations provide a framework for evaluating the regional applicability of traditional weather prediction methods such as Cabañuelas. _Source: Self-built using Python and GeoPandas._

![Colombias_Regions](https://github.com/sierraporta/cabanuelas-analysis/blob/main/figoneCaban.png)
