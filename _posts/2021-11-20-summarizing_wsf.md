---
title: "World Settlement Footprint - zonal stats and mapping"
date: 2021-10-20
--- 
## World Settlement Footprint
The World Settlement Footprint was officially launched in November 2021 at a global scale, see the [announcement here for more details](https://www.esa.int/Applications/Observing_the_Earth/Mapping_our_human_footprint_from_space)

At the World Bank, the Global Operational Support Team (GOST) have downloaded the evolution dataset, generated a VRT combining the ~5000 tiles, and uploaded to our private AWS bucket. The WSF data will be used to summarize change in the built up extent of cities globally, based on the city extents as defined in the [Urban Centre Database](https://ghsl.jrc.ec.europa.eu/ghs_stat_ucdb2015mt_r2019a.php).

The code used to summarize the WSF with the urban databases can be [found here](https://github.com/worldbank/Surviving_to_Thriving/blob/master/notebooks/ZON_URBAN_Global_SummarizeWSF.ipynb) .

## Sample maps and results
# Nairobi, Kenya
<iframe width="700" height="500" frameborder="0" title="WSF map of Washington DC" src="https://worldbank.github.io/Surviving_to_Thriving/media/WSF_Map_Nairobi.html"></iframe>

![Halifax urban built-up](https://raw.githubusercontent.com/worldbank/Surviving_to_Thriving/gh-pages/media/WSF_Evolution_Nairobi.png)

# Halifax, Nova Scotia, Canada
<iframe width="700" height="500" frameborder="0" title="WSF map of Washington DC" src="https://worldbank.github.io/Surviving_to_Thriving/media/WSF_Map_Halifax.html"></iframe>

![Halifax urban built-up](https://raw.githubusercontent.com/worldbank/Surviving_to_Thriving/gh-pages/media/WSF_Evolution_Halifax.png)

# Washington, D.C.
<iframe width="700" height="500" frameborder="0" title="WSF map of Washington DC" src="https://worldbank.github.io/Surviving_to_Thriving/media/WSF_Map_Washington D.C..html"></iframe>

![Halifax urban built-up](https://raw.githubusercontent.com/worldbank/Surviving_to_Thriving/gh-pages/media/WSF_Evolution_Washington D.C..png)

