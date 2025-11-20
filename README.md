# Bird Surveillance Dashboard

![alt text](https://github.com/emc-viroscience/bird-surveillance-dashboard/actions/workflows/deploy.yml/badge.svg)

This repository contains the source code for an interactive web dashboard visualizing arbovirus surveillance data in birds across the Netherlands from 2016 to 2022. The dashboard provides spatial and temporal insights into sampling efforts and the detection of viruses like Usutu (USUV) and West Nile Virus (WNV).

➡️ [View the live dashboard here](https://emc-viroscience.github.io/bird-surveillance-dashboard/)

## Key Features

-   Interactive Maps: Spatial distribution of captured/found birds (live and dead), with clustering for high-density areas.
-   Virus Detections: Maps highlighting locations with positive USUV and WNV cases.
-   Temporal Analysis: Bar charts showing monthly sampling efforts and virus detections over the years.
-   Seroprevalence Trends: A line chart illustrating the seasonal seroprevalence of USUV and WNV antibodies in Eurasian Blackbirds and Song Thrushes.
-   Responsive Design: Built with Quarto Dashboards for viewing on different screen sizes.

## Data Sources

The analysis is based on datasets obtained from the Pathogen Portal. The specific datasets used are: 
- Surveillance for arboviruses in dead captive birds in the Netherlands, 2016-2022 
- Surveillance for arboviruses in free ranging live birds in the Netherlands, 2016-2022 
- Surveillance for arboviruses in free ranging dead birds in the Netherlands, 2016-2022 
- Serosurveillance for arboviruses in live birds in the Netherlands, 2016-2022

## Deployment

The dashboard is automatically built and deployed to GitHub Pages via a GitHub Actions workflow defined in .github/workflows/deploy.yml. The deployment triggers on every push to the main branch.

## License

This repository contains materials under two different licenses:

-   **Source Code:** The Quarto/R source code used to generate the dashboard is licensed under the [MIT License](LICENSE).
-   **Data:** The datasets located in the `/data` directory are sourced from the [Pathogen Portal](https://www.pathogensportal.nl/arboviruses_in_birds.html) and are made available under the [CC0 1.0 Universal Public Domain Dedication](data/LICENSE.md).
