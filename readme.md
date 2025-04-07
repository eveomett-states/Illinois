# License
This data was generated using data from the Redistricting Data Hub.  Any use of this project shall also comply with restrictions on use of data and attribution requirements set forth in the Redistricting Data Hub terms and conditions found at: [https://redistrictingdatahub.org/terms-and-conditions/](https://redistrictingdatahub.org/terms-and-conditions/).

Use of this project is further governed by the terms of the [Creative Commons Attribution Noncommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/legalcode.en)

# Illinois Election Json

This shapefile was processed by Professor Ellen Veomett and her student Arbie Hsu using the corresponding jupyter notebook.  As part of the cleaning process, precincts were nested within counties and small rook adjacencies (under 30.5 m) were changed to queen adjacencies.

# **Sources**

Obtain the following data from Restricting Data Hub

[Population data](https://redistrictingdatahub.org/dataset/illinois-block-pl-94171-2020-by-table/): based on the decennial census at the Census Block level on 2020 Census Redistricting Data

[Congressional District data](https://redistrictingdatahub.org/dataset/2021-illinois-congressional-districts-approved-plan/): 2021 Illinois Congressional Districts plan enacted on 10/28/2021

[State House District data](https://redistrictingdatahub.org/dataset/2021-illinois-state-house-adopted-plan/): 2021 State House Approved Plan

[State Senate District data](https://redistrictingdatahub.org/dataset/2021-illinois-state-senate-adopted-plan/): 2021 State Senate Approved Plan

[2020 election data](https://redistrictingdatahub.org/dataset/vest-2020-illinois-precinct-and-election-results/)**:**  VEST 2020 Illinois precinct and election results

[2018 election data](https://redistrictingdatahub.org/dataset/2018-il-election-data-projected-to-2020-vtds/)**:**  VEST 2018 Illinois precinct and election results

[2020 County data](https://redistrictingdatahub.org/dataset/illinois-county-pl-94171-2020/): from 2020 Census Redistricting Data (P.L. 94-171) Shapefiles

# **Processing**

Data were cleaned and aggregated in the corresponding jupyter notebook using MGGG’s python library [maup](https://github.com/mggg/maup).

# **Metadata**

Below is a brief description of each of the listed variables in the attribute table of the VTD shapefile:

- `STATEFP20`: State FIPS code  
- `COUNTYFP20`: County FIPS code  
- `GEOID20`: VTD FIPS code  
- `PCT_CEB20`: Percentage of women who have ever given birth, based on data from the 2020 Census  
- `COUNTY_NAM20`: County name
- `CD`: Congressional district ID in 2021 enacted congressional map
- `SEND`: State Senate district for 2021 State Senate Adopted Plan
- `HDIST`: State House district for 2021 State House of Representatives Districts Plan
- `TOTPOP`: Total population in 2020 Census
- `NH_WHITE`: White, non-hispanic, population in 2020 Census
- `NH_BLACK`: Black, non-hispanic, population in 2020 Census
- `NH_AMIN`: American Indian and Alaska Native, non-hispanic, population in 2020 Census
- `NH_ASIAN`: Asian, non-hispanic, population in 2020 Census
- `NH_NHPI`: Native Hawaiian and Pacific Islander, non-hispanic, population in 2020 Census
- `NH_OTHER`: Other race, non-hispanic, population in 2020 Census
- `NH_2MORE`: Two or more races, non-hispanic, population in 2020 Census
- `HISP`: Hispanic population in 2020 Census
- `H_WHITE`: White, hispanic, population in 2020 Census
- `H_BLACK`: Black, hispanic, population in 2020 Census
- `H_AMIN`: American Indian and Alaska Native, hispanic, population in 2020 Census
- `H_ASIAN`: Asian, hispanic, population in 2020 Census
- `H_NHPI`: Native Hawaiian and Pacific Islander, hispanic, population in 2020 Census
- `H_OTHER`: Other race, hispanic, population in 2020 Census
- `H_2MORE`: Two or more races, hispanic, population in 2020 Census
- `VAP`: Total voting age population in 2020 Census
- `HVAP`: Hispanic voting age population in 2020 Census
- `WVAP`: White, non-hispanic, voting age population in 2020 Census
- `BVAP`: Black, non-hispanic, voting age population in 2020 Census
- `AMINVAP`: American Indian and Alaska Native, non-hispanic, voting age population in 2020 Census
- `ASIANVAP`: Asian, non-hispanic, voting age population in 2020 Census
- `NHPIVAP`: Native Hawaiian and Pacific Islander, non-hispanic, voting age population in 2020 Census
- `OTHERVAP`: Other race, non-hispanic, voting age population in 2020 Census
- `2MOREVAP`: Two or more races, non-hispanic, voting age population in 2020 Census
- `ATG18D`: Number of votes for 2018 Democratic attorney general candidate
- `ATG18R`: Number of votes for 2018 Republican attorney general candidate
- `AUD18D`: Number of votes for 2018 Democratic Auditor
- `AUD18R`: Number of votes for 2018 Republican Auditor
- `COC18D`: Number of votes for 2018 Democratic Corporation Commissioner candidate  
- `COC18R`: Number of votes for 2018 Republican Corporation Commissioner candidate  
- `COC18O`: Number of votes for 2018 other Corporation Commissioner candidates  
- `COC20R`: Number of votes for 2020 Republican Corporation Commissioner candidate  
- `COC20O`: Number of votes for 2020 other Corporation Commissioner candidates
- `INS18D`: Number of votes for 2018 Democratic Commissioner of Insurance
- `INS18R`: Number of votes for 2018 Republican Commissioner of Insurance
- `LAB18D`: Number of votes for 2018 Democratic Commissioner of Labor
- `LAB18R`: Number of votes for 2018 Republican Commissioner of Labor
- `LAB18O`: Number of votes for 2018 other Commissioner of Labor
- `LTG18D`: Number of votes for 2018 Democratic Lieutenant Governor
- `LTG18R`: Number of votes for 2018 Republican Lieutenant Governor
- `LTG18O`: Number of votes for 2018 other Lieutenant Governor
- `PRE16D`: Number of votes for 2016 Democratic President
- `PRE16O`: Number of votes for 2016 other party's President
- `PRE16R`: Number of votes for 2016 Republican President
- `PRE20D`: Number of votes for 2020 Democratic President
- `PRE20R`: Number of votes for 2020 Republican President
- `PRE20O`: Number of votes for 2020 other party's President
- `SPI18D`: Number of votes for 2018 Democratic Superintendent of Public Instruction  
- `SPI18O`: Number of votes for 2018 other party's Superintendent of Public Instruction  
- `SPI18R`: Number of votes for 2018 Republican Superintendent of Public Instruction  
- `TRE18O`: Number of votes for 2018 other party's Treasurer  
- `TRE18R`: Number of votes for 2018 Republican Treasurer  
- `USS16D`: Number of votes for 2016 Democratic Senate candidate  
- `USS16O`: Number of votes for 2016 other party's Senate candidate  
- `USS16R`: Number of votes for 2016 Republican Senate candidate  
- `USS20D`: Number of votes for 2020 Democratic Senate candidate  
- `USS20O`: Number of votes for 2020 other party's Senate candidate  
- `USS20R`: Number of votes for 2020 Republican Senate candidate  
