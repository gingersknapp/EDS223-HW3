# EDS223-HW3: Prioritzing Potential Aquaculture
This repository houses materials for HW3 for UCSB's Masters of Enviornmental Data Science course EDS223.  

This project creates a generalizable analysis to identify suitable locations for aquaculture of various marine food sources.  Oysters and red abalone are used as example cases.

## Repository Structure

|File/folder name               | Contents                            |
|:------------------------------|:------------------------------------|
|README.md                      | README for the repository           |
|aquaculture-analysis.qmd       | Analysis code document              |
|aquaculture-analysis.pdf       | Exportable analysis PDF             |
|.quarto/typst/packages/preview | Files for viewing aquaculture-analysis.pdf     |
|LICENSE                        | Use license                         |
|.gitignore                     | Untracked files                     | 
                                              


## Data access
Sea surface temperatures used in this analysis are obtained from [NOAA's 5km Daily Global Satellite Sea Surface Temperature Anomaly v3.1](https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php).  Measurements are averaged over four years between 2008 and 2012.  Bathymetry measurements are taken from the [General Bathymetric Chart of the Oceans (GEBCO)](doi:10.5285/e0f0bb80-ab44-2739-e053-6c86abc0289c).  Boundaries of Exclusive Economic Zones are designated based on [Marineregions.org](https://www.marineregions.org/eez.php).

## Authors
 - Olivia Knapp
 - [Annie Adams](https://github.com/annieradams) (Instructor)

## References
- Coral Reef Watch. (2018, August 1). Daily Global 5km Satellite Sea Surface Temperature Anomaly (Version 3.1). NOAA Coral Reef Watch Daily 5km satellite coral bleaching heat stress SST anomaly product (version 3.1). https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php 

- Flanders Marine Institute. (n.d.). EEZ boundaries. Marine regions. https://www.marineregions.org/eez.php 

- GEBCO Compilation Group (2022) GEBCO_2022 Grid (doi:10.5285/e0f0bb80-ab44-2739-e053-6c86abc0289c).

- Palomares, M.L.D. and D. Pauly. Editors. 2026. SeaLifeBase. World Wide Web electronic publication. www.sealifebase.org, version (06/2026).
