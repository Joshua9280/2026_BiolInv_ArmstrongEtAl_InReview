# 2026_BiolInv_ArmstrongEtAl_InReview
**Title**: Disentangling the effects of propagule pressure and disturbance on invasive plant establishment and invasion rate in a dynamic aquatic ecosystem.

**Authors**: Joshua T. Armstrong, Sara E. Kuebbing, Phoebe LaMountain, & James R. Vonesh

This repository contains all files associated with the publication in-review at Biological Invasions (2026)

The following datasets and script are those used in the analysis for this manuscript. There are a total of 2 csv files and 1 Markdown file containing all of the code and data for this manuscript. The csv "Rockpool_Prop_Press.csv" contains all of the data that was obtained from the study. The csv "FiveYearAverages.csv" contains the flood data for all of the pools. The Markdown file contains all of the code for the entire analysis of this project.

# **Description of the Data & File structure**:
The following is detailed metadata describing all of the column names and units for each of the datasets provided.

## **Rockpool_Prop_Press.csv**
- Pool_ID = This is the specific numerical identifier for the rock pools in the system (no units).
- Prop_Num = This is the propagule number treatment (number of introductions).
- Prop_Size = This is the propagule size treatment (number of fragments added).
- Prop_Size_cm2 = This is the mean surface area coverage of the propagule size treatments (cm2).
- Flood_Hgt_ft = The river height, based on gauge data, at which the pool is inundated (ft).
- Depth_cm = Mean depth of the pool (cm).
- SA_cm2 = Mean surface area of the pool (cm2).
- Volume_cm3 = Mean volume of the pool (cm3).
- Lip_cm = Mean lip height of the pool (cm).
- Can_Cov = Percent canopy cover (%)
- Other_Plant_0 = Other plants, besides Hydrilla, present in pool on day 0 (0-absent, 1-present).
- Occ_0 - Occ_84 = Hydrilla occupancy of the pool on day sampled, 0-84, (0-absent, 1-present).
- Per_Cover_0 - Per_Cover_84 = Percent coverage of the pool taken up by Hydrilla on day sampled, 0-84, (%).
- Past_Cover_14 - Past_Cover_84 = The percent coverage the sample prior to the current sampling day, 14-84, (%).
- Add_Cover_14 - Add_Cover_84 = The added percent cover added the previous sampling day, 14-84, (%).
- Hyd_Area_0 - Hyd_Area_84 = The surface area of the pool covered by Hydrilla on sampling day, 0-84 (cm2).
- Intital_wetbio_g = The initial wet biomass of Hydrilla added to the pool (g).
- Initial_drybio_g = The initial dry biomass of Hydrilla added to the pool (g).
- Final_wetbio_g = The final wet biomass of Hydrilla at the end of the experiment (g).
- Final_drybio_g = The final dry biomass of Hydrilla at the end of the experiment (g).
- Tur_prod = The presence of turions on the final sample of Hydrilla (0-absent, 1-present).

## **FiveYearAverages.csv**
- Pool_ID = This is the specific numerical identifier for the rock pools in the system (no units).
- FloodedAt = The river height, based on gauge data, at which the pool is inundated (ft).
- DaysFlooded = The total number of days a pool was flooded over a five year period (days).
- AvgDaysFlooded = The average number of days that a pool is inundated during a year (days/year).
- TotalEvent = The total number of inundation events for the pool during a five year period (events).
- AvgEvent = The average number of inundation events during a year (events/year).

# **Code/Software**
The code for this analysis was run in R (R version 4.4.1 (2024-06-14)) and the following packages were used:
- tidyverse (2.0.0)
- MASS (7.3-60.2)
- ggpubr (0.6.0)
- cowplot (1.1.3)
- dotwhisker (0.8.2)
- moments (0.14.1)
- rcompanion (2.4.36)
- glmmTMB (1.1.9)
- DHARMa (0.4.6)
- SuppDists (1.1-9.7)
- DescTools (0.99.56)
- performance (0.12.2)
- multcomp (1.4-26)
- ggeffects (1.7.0)
- jtools (2.3.0)
- interactions (1.2.0)
- knitr (1.48)
- kableExtra (1.4.0)
- ggbreak (0.1.2)
- flextable (0.9.6)
- ggfx (1.0.1)
- ggforce (0.4.2)
- lme4 (1.1-35.5)
- lmerTest (3.1-3)
- smplot2 (0.2.5)
- car (3.1-2)
- marginaleffects (0.30.0)
- betareg (3.2-4)

pscl (1.5.9)

