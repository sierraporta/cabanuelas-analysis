[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange.svg)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![License: MIT](https://img.shields.io/badge/Climatic_Analysis-CABAÑUELAS-blue)](CABAÑUELAS)
[![License: MIT](https://img.shields.io/badge/Colombia_Climatic-CABAÑUELAS-green)](Colombia)
[![License: MIT](https://img.shields.io/badge/Climatic_Culture-Perceptions-green)](Culture)


# Cabañuelas´s Analysis
_Weather prediction has long been central to human societies, supporting decisions in agriculture, water management, and risk reduction. Although contemporary forecasting is dominated by numerical modeling, satellite and in-situ observing systems, and statistical post-processing, many traditional communities have also developed practical, experience-based rules rooted in repeated local observation. One widely cited example is the Cabañuelas, which remains in use in Colombia and other parts of Latin America. In its common formulation, conditions observed across the first twenty-four days of January are interpreted as indicative of the sequence of climatic tendencies over the subsequent months._

_Accounts of the Cabañuelas are frequently traced to premodern agrarian societies. Historical and ethnographic sources report analogous practices in Mesoamerica, including Mayan contexts and references linked to Aztec seasonal knowledge, as well as traditions documented in the Iberian Peninsula prior to Spanish colonization of the Americas. In settings where livelihoods depended strongly on seasonal timing, such methods served as informal guides to expected shifts, often drawing on cues such as lunar cycles and recurrent atmospheric patterns. Through later cultural transmission and adaptation, the practice spread to Latin America and evolved into the variants still recognized across the region today._

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

## Colombia´s Regions:
**Natural Regions of Colombia.** The map shows the five major geographical regions of Colombia—Caribbean, Andean, Pacific, Orinoquía, and Amazon—each with distinct climatic characteristics. These variations provide a framework for evaluating the regional applicability of traditional weather prediction methods such as Cabañuelas. _Source: Self-built using Python and GeoPandas._

![Colombias_Regions](https://github.com/sierraporta/cabanuelas-analysis/blob/main/figoneCaban.png)
