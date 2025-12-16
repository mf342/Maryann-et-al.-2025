***Measuring the Distances to Asteroids from One Observatory in One Night with Upcoming All-Sky Telescopes (Maryann et al. 2025)***
----------------------------------------------------------------------------------------------------------------------------------------------------------
This repository contains all code and datasets used to generate the figures and tables in the above paper. In total, the paper includes 10 figures and 5 tables.

The repository is organized by figure number, and each folder contains:
1) the synthetic or real-time datasets used in the manuscript,
2) the Python code required to reproduce each plot, and
3) any supplementary files needed for analysis.

(_To reproduce any image or table in the paper, please download all the files in the folders, and edit the path where the input files are located on your device/cloud. When this is done, and you hit run, the entire code should complete the final image._)
   
Data Sources: 
All synthetic data were obtained from the NASA JPL Horizons system (hereafter _Horizons_): https://ssd.jpl.nasa.gov/horizons/. 
Real-time data were taken with the Panchromatic Robotic Optical Monitoring and Polarimetry Telescopes (PROMPT) on Cerro Tololo in Chile (Reichart et al. 2005) during the observations described in the manuscript.

Licensing: This repository is released under the MIT License, allowing reuse with attribution.

A tagged version of this repository corresponding to the final, post–peer-review version of the manuscript is archived in Zenodo, and includes a DOI for citation, which is also included in the manuscript.

For questions or collaboration inquiries, please contact: maryannbenny.fernandes@duke.edu

----------------------------------------------------------------------------------------------------------------------------------------------------------
**#Repository Structure**

**Figure 1:** 
Synthetic _Horizons_ data for asteroid 2024 ON (Sept 5–6, 2024, 1 hour cadence, 48 observations, addition of randomly generated 20 mas noise) and code to reproduce the figure. 

**Figure 2:** 
(Similar to Figure 1) Synthetic _Horizons_ data for asteroid 4953/1990 MU (Oct 30–31, 2024, 1 hour cadence, 48 observations, addition of randomly generated 20 mas noise) and corresponding code.

**Figure 3:** 
Synthetic _Horizons_ data for 20 asteroids over a short observational arc of ~4 hours (Sept 5–6, 2024, added randomly generated 20 mas noise) with code for distance-measurements.

**Figure 4:** 
(Similar to Figure 3) Synthetic _Horizons_ data for the same 20 asteroids over a multi-night arc, five days (Sept 5–9, 2024, three observations per night added randomly generated 20 mas noise) with code for distance measurements.

**Figure 5-7 & Table 1-3:** 
Figure 5 compares real-time PROMPT telescope observations of asteroids 2024 ON and 4953/1990 MU with corresponding _Horizons_ ephemeris data as seen in Tables 2 and 3. 
Figure 6 uses real-time PROMPT observations (time and RA) of 2024 ON (~4-hour arc) as seen in Table 2. The results of the data measurement for 2024 ON is in Table 1, column 2. 
(Similar to Figure 6) Figure 7 uses real-time PROMPT observations (time and RA) of 4953/1990 MU (~7-hour arc) as seen in Table 3. The results of the data measurement for 4953/1990 MU is in Table 1, column 3. 

**Figure 8:** 
Comparison of the topocentric parallax distance measurement for multiple asteroids as seen in figures 3 and 4, for single and multiple night observations against _Find_Orb_, the orbit determination software.

**Figure 9 & Table 4:** 
Using _Find_Orb_, among the 20 asteroids discussed in Section 2.3, the orbital determination of the asteroids is computed for two observational cases: Observations with diversity and observations without diversity. The ratio of the uncertainties in the semi-major axis for both cases is done for nine asteroids against their distance dependence from Earth. The dataset in the folder to reproduce this image and table includes the astrometry inputted into _Find_Orb_ (the '(asteroid name).obs' file), code, and a pdf containing screenshots of the orbital data from _Find_Orb_ for each of the nine asteroids for both the cases.

**Figure 10 & Table 5:** 
Fractional distance uncertainty and script for multi-survey comparison.
