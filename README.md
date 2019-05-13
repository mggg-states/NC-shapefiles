# North Carolina Election Shapefile
This shapefile was obtained from the North Carolina General Assembly’s website and processed by members of the Metric Geometry and Gerrymandering Group (MGGG). 

## Sources
North Carolina election data and shapefiles come from the [North Carolina General Assembly’s 2016 Redistricting Reference Data](https://www.ncleg.gov/RnR/Redistricting/BaseData2016). Demographic data come from the [National Historical Geographic Information System (NHGIS)](https://www.nhgis.org).

## Processing
Demographic data was aggregated from the census block level to VTDs using the General Assembly’s Block Level Key. [Roundoff](https://github.com/gerrymandr/Preprocessing) was used to assign districts from the 2011 enacted plan, 2016 enacted plan, and the judge’s plan to VTDs.

## Metadata
* `ALAND10`: Area of VTD land in square meters
* `AWATER10`: Area of VTD water in square meters
* `VTD`: VTD unique identifier
* `County`: County FIPS
* `VTD_Key`: VTD unique identifier
* `VTD_Name`: VTD name
* `PL10AA_TOT`: Total population
* `PL10VA_TOT`: Total voting age population
* `EL08G_GV_D`: Number of votes for 2008 Democratic gubernatorial candidate
* `EL08G_GV_R`: Number of votes for 2008 Republican gubernatorial candidate
* `EL08G_GV_L`: Number of votes for 2008 Libertarian gubernatorial candidate
* `EL08G_GV_T`: Total number of votes for 2008 gubernatorial candidates
* `EL08G_USS_`: Number of votes for 2008 Democratic US Senate candidate
* `EL08G_US_1`: Number of votes for 2008 Republican US Senate candidate
* `EL08G_US_2`: Number of votes for 2008 Libertarian US Senate candidate
* `EL08G_US_3`: Number of votes for 2008 write-in US Senate candidates
* `EL08G_US_4`: Total number of votes for 2008 US Senate candidates
* `EL10G_USS_`: Number of votes for 2008 Democratic US Senate candidate
* `EL10G_US_1`: Number of votes for 2008 Republican US Senate candidate
* `EL10G_US_2`: Number of votes for 2008 Libertarian US Senate candidate
* `EL10G_US_3`: Number of votes for 2008 write-in US Senate candidates
* `EL10G_US_4`: Total number of votes for 2008 US Senate candidates
* `EL12G_GV_D`: Number of votes for 2012 Democratic gubernatorial candidate
* `EL12G_GV_R`: Number of votes for 2012 Republican gubernatorial candidate
* `EL12G_GV_L`: Number of votes for 2012 Libertarian gubernatorial candidate
* `EL12G_GV_W`: Number of votes for Donald Kreamer as 2012 gubernatorial candidate
* `EL12G_GV_1`: Number of votes for 2012 write-in gubernatorial candidates
* `EL12G_GV_T`: Total number of votes for 2012 gubernatorial candidates
* `EL14G_USS_`: Number of votes for 2014 Democratic US Senate candidate
* `EL14G_US_1`: Number of votes for 2014 Republican US Senate candidate
* `EL14G_US_2`: Number of votes for 2014 Libertarian US Senate candidate
* `EL14G_US_3`: Number of votes for 2014 write-in US Senate candidates
* `EL14G_US_4`: Total number of votes for 2014 US Senate candidates
* `Shape_Leng`: VTD perimeter in meters
* `Shape_Area`: VTD area in square meters
* `EL12G_PR_D`: Number of votes for 2012 Democratic presidential candidate
* `EL12G_PR_R`: Number of votes for 2012 Republican presidential candidate
* `EL12G_PR_L`: Number of votes for 2012 Libertarian presidential candidate
* `EL12G_PR_W`: Number of votes for 2012 write-in presidential candidate
* `EL12G_PR_1`: Number of votes for 2012 write-in presidential candidate
* `EL12G_PR_T`: Total number of votes for 2012 presidential candidates
* `EL16G_PR_D`: Number of votes for 2016 Democratic presidential candidate
* `EL16G_PR_R`: Number of votes for 2016 Republican presidential candidate
* `EL16G_PR_L`: Number of votes for 2016 Libertarian presidential candidate
* `EL16G_PR_W`: Number of votes for 2016 write-in presidential candidate
* `EL16G_PR_T`:  Total number of votes for 2016 presidential candidates
* `EL16G_USS_`: Number of votes for 2016 Republican US Senate candidate
* `EL16G_US_1`: Number of votes for 2016 Democratic US Senate candidate
* `EL16G_US_2`: Number of votes for 2016 Libertarian US Senate candidate
* `EL16G_US_3`: Total number of votes for 2016 US Senate candidates
* `EL16G_GV_D`: Number of votes for 2016 Democratic gubernatorial candidate
* `EL16G_GV_R`: Number of votes for 2016 Republican gubernatorial candidate
* `EL16G_GV_L`: Number of votes for 2016 Libertarian gubernatorial candidate
* `EL16G_GV_T`: Total number of votes for 2016 gubernatorial candidates
* `BPOP`: Black (including Black and Hispanic) population
* `nBPOP`: Non-Black population
* `judge`: District from Judge’s plan
* `newplan`: District from 2016 plan
* `oldplan`: District from 2011 plan
* `TOTPOP`: Total population 
* `NH_WHITE`: White, non-hispanic, population
* `NH_BLACK`: Black, non-hispanic, population
* `NH_AMIN`: American Indian and Alaska Native, non-hispanic, population
* `NH_ASIAN`: Asian, non-hispanic, population
* `NH_NHPI`: Native Hawaiian and Pacific Islander, non-hispanic, population
* `NH_OTHER`: Other race, non-hispanic, population
* `NH_2MORE`: Two or more races, non-hispanic, population
* `HISP`: Hispanic population
* `H_WHITE`: White, hispanic, population
* `H_BLACK`: Black, hispanic, population
* `H_AMIN`: American Indian and Alaska Native, hispanic, population
* `H_ASIAN`: Asian, hispanic, population
* `H_NHPI`: Native Hawaiian and Pacific Islander, hispanic, population
* `H_OTHER`: Other race, hispanic, population
* `H_2MORE`: Two or more races, hispanic, population
* `VAP`: Total voting age population
* `HVAP`: Hispanic voting age population
* `WVAP`: White, non-hispanic, voting age population
* `BVAP`: Black, non-hispanic, voting age population
* `AMINVAP`: American Indian and Alaska Native, non-hispanic, voting age population
* `ASIANVAP`: Asian, non-hispanic, voting age population
* `NHPIVAP`: Native Hawaiian and Pacific Islander, non-hispanic, voting age population
* `OTHERVAP`: Other race, non-hispanic, voting age population
* `2MOREVAP`: Two or more races, non-hispanic, voting age population


## Rating
We give this shapefile an A rating. All data was obtained from the state government and was processed by MGGG staff.
