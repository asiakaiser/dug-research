# dug-research

Datasets and code for the manuscript:

**Urbanization and wealth alter arthropod biodiversity and pollination services in community gardens**  
Asia Kaiser $^1$, Noah Mayer $^1$, Rene Aronson $^1$, Julian Resasco $^1$

$^1$ Department of Ecology and Evolutionary Biology, The University of Colorado Boulder

---
### Description of Methods

This repository contains code and data to analyze arthropod biodiversity and cucumber crop outcomes across Denver Urban Gardens study sites  

[Project Description](https://www.asiakaiser.com/research/denver-urban-gardens-research)

---

### Files
#### Analyses

1. `analyses/Analysis_DUG.Rmd`  
   This R Markdown file contains the code to run all Bayesian regression models described in manuscript sections *Local and Landscape Variables and Wealth Index*, *Arthropod Abundance and Bee Diversity*, and *Structural Equation Path Analysis*. 

2. `analyses/CommunityAnalysis_DUG.Rmd`  
   This R Markdown file contains the code for NMDS ordination, the PERMANOVA to examine differences in community composition, and the Multivariate Generalized Linear Models to examine the drivers of differences in community composition, described in manuscript section *Community Dissimilarity*

#### Data Prep

3. `analyses/DataCleaning_DUG.Rmd`  
   This R Markdown file contains the code used to get data into the proper format to run analyses. It also contains the code for the rarefaction of GBIF floral observations and bee species.

4. `analyses/DataExtraction_GBIF.Rmd`  
   This R Markdown file contains the code used to assign GBIF observations to 1-km buffers around DUG sites. 

5. `analyses/DataExtraction_LandCover.Rmd`  
   This R Markdown file contains the code used to extract and summarize raster data from USGS National Land Use Land Cover rasters, Fractional Impervious Surface, and Tree Canopy Cover.

---

### External Datasets and Citations

1. United States Geological Survey. (2025). Annual National Land Cover Database (NLCD) Collection 1 Products (ver. 1.1, June 2025) [Pdf,png]. U.S. Geological Survey. (https://doi.org/10.5066/P94UXNTS)
2. GBIF.org (27 February 2026) GBIF Occurrence Download (https://doi.org/10.15468/dl.9r9f9t)   
---
