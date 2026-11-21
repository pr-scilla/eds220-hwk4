# Visualizing Fire Scars Through False Color
## EDS 220 Homework Assignment #4

## About

The January 2025 Eaton and Palisades fires consumed more than [38,000 acres](https://www.news.caloes.ca.gov/a-year-after-the-la-fires-pacific-palisades-and-altadena-communities-recover/) of Los Angeles County. Tens of thousands of residents were displaced, thousands of structures were destroyed, and large areas of the foothills and coast sustained severe damage.

This assignment explores the impacts of the Eaton and Palisades fires through data exploration and visualization of the burn scars in true color and false color imagery.

The code outputs are true color imagery of the Los Angeles area and a map of the Eaton and Palisades fire perimeters overlaying false color imagery of the Los Angeles area.

## Repository Structure:

```{python}
eds220-hwk4
└─── README.md
└─── hwk4-task2-false-color-PIERCE.ipynb      # notebook containing all assignment code
└───.gitignore
     └───data                                 # folder containing data files for assignment
         └─── Eaton_Perimeter_20250121
         |   └─── Eaton_Perimeter_20250121 shapefile
         └─── Palisades_Perimeter_20250121
         |   └─── Palisades_Perimeter_20250121 shapefile
         └─── landsat8-2025-02-23-palisades-eaton.nc
```
## Data Access

Landsat Collection 2 Level-2 atmospherically corrected surface reflectance data (collected by the Landsat 8 satellite) were prepared by the EDS 220 instructing team and downloaded with permission from the [course shared data Google Drive](https://drive.google.com/drive/folders/1USqhiMLyN8GE05B8WJmHabviJGnmAsLP) on the [EDS 220 Assignment 4 page](https://meds-eds-220.github.io/MEDS-eds-220-course/assignments/assignment4-palisades-eaton-fires.html#ref-bennett_politics_2022). The `landsat8-2025-02-23-palisades-eaton.nc` file was saved locally to the `data` folder within the eds220-hwk4 repository.

Eaton and Palisades fire perimeter data were downloaded from the [County of Los Angeles Open Data website](https://data.lacounty.gov/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about) and saved locally to the `data` folder within the eds220-hwk4 repository. 

## Contributors

Author: [Priscilla Pierce](https://github.com/pr-scilla)

## References and Data Sources

[EDS 220: Working with Environmental Datasets](https://meds-eds-220.github.io/MEDS-eds-220-course/) Instructor: Carmen Galaz García

County of Los Angeles. (2026). Eaton_Perimeter_20250121 [Dataset]. County of Los Angeles Open Data. Retrieved November 2026 from (https://data.lacounty.gov/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about)

County of Los Angeles. (2026). Palisades_Perimieter_20250121 [Dataset]. County of Los Angeles Open Data. Retrieved November 2026 from https://data.lacounty.gov/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about

[Microsoft Planetary Computer](https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2). (2025). Landsat Collection 2 Level-2 atmospherically corrected surface reflectance data [Dataset]. Landsat Collection 2 Level-2. Retrieved November 2026 from course shared Google Drive (https://drive.google.com/drive/folders/1USqhiMLyN8GE05B8WJmHabviJGnmAsLP)