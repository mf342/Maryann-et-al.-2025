# Maryann-et-al.-2025

This repository contains all code and datasets used to generate the figures and tables in Maryann et al. (2025). In total, the paper includes 10 figures and 5 tables.

The repository is organized by figure number, and each folder contains:
1) the synthetic or real-time datasets used in the manuscript,
2) the Python code required to reproduce each plot, and
3) any supplementary files needed for analysis.

Data Sources: 
All synthetic data were obtained from the NASA JPL Horizons system: https://ssd.jpl.nasa.gov/horizons/
Real-time data were taken with the PROMPT telescopes in Chile during the observations described in the manuscript.

Licensing: This repository is released under the MIT License, allowing reuse with attribution.

A tagged version of this repository corresponding to the final, post–peer-review version of the manuscript is deposited in Zenodo to ensure a long-term archive and DOI for citation. The DOI is included in the final paper using the AASTeX \dataset[]{}{} macro.

For questions or collaboration inquiries, please contact: maryannbenny.fernandes@duke.edu

----------------------------------------------------------------------------------------------------------------------------------------------------------
**#Repository Structure**

**Figure 1:** Synthetic Horizons data for asteroid 2024 ON (Sept 5–6, 2024, 1-hr cadence, 48 observations, added randomly generated 20 mas noise) and code to reproduce the figure.

**Figure 2:** Synthetic Horizons data for asteroid 4953 (Oct 30–31, 2024, 1-hr cadence, 48 observations, added randomly generated 20 mas noise) and corresponding code.

**Figure 3:** Synthetic Horizons data for 20 asteroids over a short observational arc (Sept 5–6, 2024, added randomly generated 20 mas noise) with code for distance-measurement performance plots.

**Figure 4:** Synthetic Horizons data for the same 20 asteroids over a multi-night arc (Sept 5–9, 2024, added randomly generated 20 mas noise). Includes code for reproducing distance-comparison plots.

**Figure 5-7 & Table 1-3:** Figure 5 uses real-time PROMPT telescope observations of 2024 ON and 4953, aligned with corresponding Horizons predictions as seen in Table 2 and 3. In Figure 6, only the real-time PROMPT data for 2024 ON (~4 hr arc) with scripts implementing Eq. 1 from the manuscript to compute distance and error is used. Similarily, we do the same for asteroid 49533/1990 MU in Figure 7. The fit results from Eq.1 and the distance measurments from Figure 6 and 7 is mentioned in Table 1. 

**Figure 8:** Comparism of distances measurements of asteroid discussed in figures 3 and 4 with distances computed from the Find_Orb software. 

**Figure 9 & Table 4:** Find_Orb-based uncertainty analysis for two observational cases: Observations with diversity and observations without diversity. The dataset includes input observational files, scripts, and visualizations from Find_Orb.

**Figure 10 & Table 5:** Fractional distance uncertainty and script for multi-asteroid comparisons.
