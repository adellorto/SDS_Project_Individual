# Spatial Data Science Assignments

This repository contains a set of three assignments completed for the course **Spatial Data Science** of the MSc in *Engineering and Policy Analysis* at TU Delft. The work was carried out by **Alessandro Dell'Orto**.

The data used in the notebooks is not included in this repository due to the large size of the original datasets.

## Assignment 1 – Data Collection and Wrangling

`Assignment_1.ipynb` introduces basic data handling for spatial analysis. Using socio‑economic statistics from the [Den Haag Cijfers](https://denhaag.incijfers.nl/) database, the notebook walks through:

1. Downloading and summarising the raw CSV files.
2. Subsetting the variables of interest and selecting a single year of data.
3. Handling missing values by dropping incomplete cases and filling where appropriate.
4. Reshaping the data from long to wide format (melt and pivot) so each neighbourhood becomes a row and selected indicators are columns.
5. Saving the cleaned dataset for later use.

## Assignment 2 – Mapping Employment Data

`Assignment_2.ipynb` focuses on merging different data sources from the **SHRUG** database of India. Employment records from the economic census are joined with census attributes and subdistrict shapefiles. After creating a ratio of female to total employment, high‑value areas are visualised on a map using **GeoPandas**. The notebook demonstrates spatial joins and basic thematic mapping.

## Assignment 3 – Advanced Spatial Analysis

`Assignment_3.ipynb` revisits the childcare and female employment hypothesis with a deeper exploration of the SHRUG dataset. The workflow is organised in several tasks:

- **Task 0 – Problem statement:** outlines the research question and lists the variables taken from SHRUG, such as female population, counts of maternity and child welfare centres, and employment statistics.
- **Task 1 – Exploratory Data Analysis:** uses scatter plots, density plots and correlation measures to inspect relationships. Local spatial autocorrelation is assessed with Moran’s I and LISA cluster maps.
- **Task 2 – Model choice:** discusses regression versus unsupervised learning and proceeds with dimensionality reduction (PCA) followed by *k*-means clustering to group districts with similar characteristics.
- **Task 3 – Critical reflection:** evaluates potential sources of bias and summarises insights from the clustering results.

---

The notebooks serve as small studies on spatial data handling, visualisation and exploratory modelling. They can be used as reference for similar analyses once the required datasets are obtained from their original sources.
