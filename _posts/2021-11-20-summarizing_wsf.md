---
title: "World Settlement Footprint - zonal stats and mapping"
date: 2021-10-20
--- 
## World Settlement Footprint
The World Settlement Footprint was officially launched in November 2021 at a global scale, see the [announcement here for more details](https://www.esa.int/Applications/Observing_the_Earth/Mapping_our_human_footprint_from_space)

At the World Bank, the Global Operational Support Team (GOST) have downloaded the evolution dataset, generated a VRT combining the ~5000 tiles, and uploaded to our private AWS bucket. The WSF data will be used to summarize change in the built up extent of cities globally, based on the cityu extents as defined in the [Urban Centre Database](https://ghsl.jrc.ec.europa.eu/ghs_stat_ucdb2015mt_r2019a.php).

The code used to summarize the WSF with theurban databases can be [found here](https://github.com/worldbank/Surviving_to_Thriving/blob/master/notebooks/ZON_URBAN_Global_SummarizeWSF.ipynb) .

## Sample maps and Results
# Washington DC
<iframe width="500" height="400" frameborder="0" title="WSF map of Washington DC" src="https://raw.githubusercontent.com/worldbank/Surviving_to_Thriving/master/images/WSF_Map_Washington%20D.C..html"></iframe>

