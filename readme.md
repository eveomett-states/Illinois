# Illinois Election Shapefile

This shapefile was processed by Professor Ellen Veomett and her student Arbie Hsu.

# **Sources**

Obtain the following data from Restricting Data Hub

[Population data](https://redistrictingdatahub.org/dataset/illinois-block-pl-94171-2020-by-table/): based on the decennial census at the Census Block level on 2020 Census Redistricting Data

[Congressional District data](https://redistrictingdatahub.org/dataset/2021-illinois-congressional-districts-approved-plan/): 2021 Illinois Congressional Districts plan enacted on 10/28/2021

[State House District data](https://redistrictingdatahub.org/dataset/2021-illinois-state-house-adopted-plan/): 2021 State House Approved Plan

[State Senate District data](https://redistrictingdatahub.org/dataset/2021-illinois-state-senate-adopted-plan/): 2021 State Senate Approved Plan

[2020 election data](https://redistrictingdatahub.org/dataset/vest-2020-illinois-precinct-and-election-results/)**:**  VEST 2020 Illinois precinct and election results

[2018 election data](https://redistrictingdatahub.org/dataset/2018-il-election-data-projected-to-2020-vtds/)**:**  VEST 2018 Illinois precinct and election results

# **Processing**

Demographic data were aggregated from the census block level and precincts were assigned to districts using [MGGG's proration software](https://github.com/mggg/maup). Election data were also prorated onto VTDs from the original precinct shapefile using the `maup` package.

# **Metadata**

Below is a brief description of each of the listed variables in the attribute table of the VTD shapefile:

- `STATEFP20`: State FIPS code
- `COUNTYFP20`: County FIPS code
- `VTDST20`: Voting tabulation district FIPS code
- `GEOID20`: VTD FIPS code
- `NAME20`: Voting tabulation district name
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
- `ATG18O`: Number of votes for 2018 other party's attorney general candidate
- `GOV18D`: Number of votes for 2018 Democratic gubernatorial candidate
- `GOV18R`: Number of votes for 2018 Republican gubernatorial candidate
- `GOV18O`: Number of votes for 2018 other party's gubernatorial candidate
- `PRE20D`: Number of votes for 2020 Democratic presidential candidate
- `PRE20R`: Number of votes for 2020 Republican presidential candidate
- `PRE20O`: Number of votes for 2020 other party's presidential candidate
- `SOS18D`: Number of votes for 2018 Democratic Secretary of State
- `SOS18R`: Number of votes for 2018 Republican Secretary of State
- `SOS18O`: Number of votes for 2018 other party's Secretary of State
- `TRE18D`: Number of votes for 2018 Democratic Treasurer
- `TRE18R`: Number of votes for 2018 Republican Treasurer
- `TRE18O`: Number of votes for 2018 other party's Treasurer
- `USS20D`: Number of votes for 2020 Democratic senate candidate
- `USS20R`: Number of votes for 2020 Republican senate candidate
- `USS20O`: Number of votes for 2020 other party's senate candidate
- `COM18D`: Number of votes for 2018 Democratic Comptroller
- `COM18R`: Number of votes for 2018 Republican Comptroller
- `COM18O`: Number of votes for 2018 other party's Comptroller

# **Projection**

The shapefile uses a UTM NAD83 projection (EPSG: 4269).