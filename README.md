# Spatial Epidemiology and Firearm Violence Research - Case Study in R/RStudio


## 1. Overview 

This repository contains a demonstration for using R/RStudio with firearm violence data as part of "The Promise and Pitfalls of Spatial Epidemiology in Firearm Violence Research" Workshop presented by the [GAPS Lab](https://www.thegapslab.org) at the 2024 National Research Conference for the Prevention of Firearm-Related Harms.


## 2. Repository Structure

- `spatial_epi_firearm_conference.Rmd`: code (RMarkdown file) for the demo
- `Data`: data needed for demo


## 3. Data Sources

We used these data sources for the demo:

- [NYC Open Data](https://opendata.cityofnewyork.us/): data generated by various NYC agencies available for public use
  - [Heat Vulnerability Index Rankings](https://data.cityofnewyork.us/Health/Heat-Vulnerability-Index-Rankings/4mhf-duep/about_data)
  - [NYPD Shooting Incident Data (Historic)](https://data.cityofnewyork.us/Public-Safety/NYPD-Shooting-Incident-Data-Historic-/833y-fsy8/about_data)
  - [Borough Boundaries](https://data.cityofnewyork.us/City-Government/Borough-Boundaries/tqmj-j8zm)
- US Census Bureau
  - [TIGER/Line ZIP Code Tabulation Areas Shapefiles](https://www.census.gov/cgi-bin/geo/shapefiles/index.php)


## 4. Requirements

You will need the following software and R packages to complete the demo.

### 4.1. Software

Download the following software:

-   [R](https://cran.r-project.org/bin/windows/base/)
-   [RStudio](https://www.rstudio.com/products/rstudio/download/#download) or another R graphical user interface

### 4.2. R packages

1.  Run the following code in R to install the necessary packages:

`install.packages(c('tidyverse','janitor','viridis','lubridate','sf','spdep'), dependencies = TRUE)`
`install.packages("INLA",repos=c(getOption("repos"),INLA="https://inla.r-inla-download.org/R/stable"), dep=TRUE)`

2.  We used the following versions of software and packages:

-   **Software**:
    -   *R:* 4.4.1 ("Race for Your Life")
    -   *RStudio:* 2024.09.1+394 ("Cranberry Hibiscus")
-   **Packages**:
    -   *`tidyverse`:* 2.0.0
    -   *`janitor`:* 2.2.0
    -   *`viridis`:* 0.6.5
    -   *`lubridate`:* 1.9.3
    -   *`sf`:* 1.0-16
    -   *`spdep`:* 1.3-3
    -   *`INLA`:* 24.05.10

### 4.3. Data
To download the data, refer to our code: `spatial_epi_firearm_conference.Rmd`

## 5. Cloning this Repository with RStudio

Below are steps to clone this repository to your local device with RStudio. Please refer to this [link](https://resources.github.com/github-and-rstudio/) for more information about using git in RStudio.

1.  On top this page, click on `Code` and copy the link to this git repository (starts with <https://github.com/>...).
2.  Open RStudio.
3.  In RStudio, click on `File` → `New Project...` → `Version Control` → `Git`.
4.  Under "Repository URL", paste the link of the git repository.
5.  Under "Project directory name", name your project directory.
6.  Under "Create project as subdirectory of:", select the folder in which you would like your project directory to be located.
7.  Click on `Create Project` when you are done to clone your repository!
