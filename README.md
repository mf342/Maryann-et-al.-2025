# Maryann-et-al.-2025

This repository contains all code and datasets used to generate the figures and tables in Maryann et al. (2025). In total, the paper includes 10 figures and 5 tables.

The repository is organized by figure number, and each folder contains:
1) the synthetic or real-time datasets used in the manuscript,
2) the Python code required to reproduce each plot, and
3) any supplementary files needed for analysis.

Data Sources: 
All synthetic data were obtained from the NASA JPL Horizons system (hereafter _Horizons_): https://ssd.jpl.nasa.gov/horizons/
Real-time data were taken with the PROMPT telescopes in Chile during the observations described in the manuscript.

Licensing: This repository is released under the MIT License, allowing reuse with attribution.

A tagged version of this repository corresponding to the final, post–peer-review version of the manuscript is archived in Zenodo, and includes a DOI for citation, which is also included in the manuscript.

For questions or collaboration inquiries, please contact: maryannbenny.fernandes@duke.edu

----------------------------------------------------------------------------------------------------------------------------------------------------------
**#Repository Structure**
To reproduce any plot, you can download the contents in the following folders, and update the file paths where the files are stored. Once this is done, you should be able to generate all the plots as seen in the paper. 

**Figure 1:** Synthetic Horizons data for asteroid 2024 ON (Sept 5–6, 2024, 1 hour cadence, 48 observations, addition of randomly generated 20 mas noise) and code to reproduce the figure. 

**Figure 2:** Synthetic Horizons data for asteroid 4953/1990 MU (Oct 30–31, 2024, 1 hour cadence, 48 observations, addition of randomly generated 20 mas noise) and corresponding code.

**Figure 3:** Synthetic Horizons data for 20 asteroids over a short observational arc of ~4 hours (Sept 5–6, 2024, added randomly generated 20 mas noise) with code for distance-measurements.

**Figure 4:** Synthetic Horizons data for the same 20 asteroids over a multi-night arc, five days, three observations per night (Sept 5–9, 2024, added randomly generated 20 mas noise) with code for distance measurements.

**Figure 5-7 & Table 1-3:** Figure 5 compares real-time PROMPT observations of 2024 ON and 4953/1990 MU with corresponding Horizons predictions; associated results appear in Tables 2 and 3. Figure 6 uses real-time PROMPT observations of 2024 ON (~4-hour arc) as seen in Table 2 to compute distance using Eq. 1 in the manuscript; results appear in Table 1. Figure 7 applies the same analysis to 4953/1990 MU (~7-hour arc) as seen in Table 3, with results also included in Table 1.

**Figure 8:** Comparison of distance measurements from figures 3 and 4 with Find_Orb for both single and multiple night observations.

**Figure 9 & Table 4:** Find_Orb-based orbital uncertainty comparing two observational cases: Observations with diversity and observations without diversity. The dataset includes input observational files into Find_Orb (file named with .obs extension), code, and visualizations from Find_Orb.

**Figure 10 & Table 5:** Fractional distance uncertainty and script for multi-survey comparison.
