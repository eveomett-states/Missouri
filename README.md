# License
This data was generated using data from the Redistricting Data Hub.  Any use of this project shall also comply with restrictions on use of data and attribution requirements set forth in the Redistricting Data Hub terms and conditions found at: [https://redistrictingdatahub.org/terms-and-conditions/](https://redistrictingdatahub.org/terms-and-conditions/).

Use of this project is further governed by the terms of the [Creative Commons Attribution Noncommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/legalcode.en)

# Missouri Json and Shapefile

This shapefile was processed by Professor Ellen Veomett and her students Arbie Hsu and Alusi, using the corresponding jupyter notebook. As part of the cleaning process, precincts were nested within counties and small rook adjacencies (under 30.5 m) were changed to queen adjacencies.

# **Sources**

The following obtained from [Redistricting Data Hub](https://redistrictingdatahub.org/) on June, 2024:

[Population data](https://redistrictingdatahub.org/dataset/missouri-block-pl-94171-2020-by-table/): based on the decennial census at the Census Block level on 2020 Census Redistricting Data

[Congressional District data](https://redistrictingdatahub.org/dataset/2022-missouri-congressional-districts-approved-plan/): 2022 Congressional Districts Approved Interim Plan

[State House District data](https://redistrictingdatahub.org/dataset/2022-missouri-state-house-of-representatives-approved-plan/): 2022 State House Approved Interim Plan

[State Senate District data](https://redistrictingdatahub.org/dataset/2022-missouri-state-senate-approved-plan/): 2022 State Senate Districts Interim Plan from

[2020 election data](https://redistrictingdatahub.org/dataset/vest-2020-missouri-precinct-and-election-results/): VEST 2020 precinct and election results

[2018 election data](https://redistrictingdatahub.org/dataset/vest-2018-missouri-precinct-and-election-results/): VEST 2018 precinct and election results 

[2016 election data](https://redistrictingdatahub.org/dataset/vest-2016-missouri-precinct-and-election-results/): VEST 2016 precinct and election results

[2020 county data](https://redistrictingdatahub.org/dataset/missouri-county-pl-94171-2020/) from 2020 Census Redistricting Data (P.L. 94-171) Shapefiles

# **Processing**

Data were cleaned and aggregated in the corresponding jupyter notebook using MGGG’s python library [maup](https://github.com/mggg/maup).
# **Metadata**

Below is a brief description of each of the listed variables in the attribute table of the VTD shapefile:

- `STATEFP20`: State FIPS code of 2020
- `COUNTYFP20`: County FIPS code of 2020
- `NAME20`: Voting tabulation district name of 2020
- `CD`: Congressional district ID in 2022 enacted congressional map
- `SEND`: State Senate district for 2022 State Senate Adopted Plan
- `HDIST`: State House district for 2022 State House of Representatives Districts Plan
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
- `ATG16D`: Number of votes for 2016 Democratic attorney general candidate
- `ATG16R`: Number of votes for 2016 Republican attorney general candidate
- `ATG20D`: Number of votes for 2020 Democratic attorney general candidate
- `ATG20R`: Number of votes for 2020 Republican attorney general candidate
- `ATG20O`: Number of votes for 2020 other party's attorney general candidate
- `AUD18D`: Number of votes for 2018 Democratic Auditor
- `AUD18O`: Number of votes for 2018 other party's Auditor
- `AUD18R`: Number of votes for 2018 Republican Auditor
- `GOV16R`: Number of votes for 2016 Republican gubernatorial candidate
- `GOV16D`: Number of votes for 2016 Democratic gubernatorial candidate
- `GOV16O`: Number of votes for 2016 other party's gubernatorial candidate
- `GOV20R`: Number of votes for 2020 Republican gubernatorial candidate
- `GOV20D`: Number of votes for 2020 Democratic gubernatorial candidate
- `GOV20O`: Number of votes for 2020 other party's gubernatorial candidate
- `LTG16D`: Number of votes for 2016 Democratic Lieutenant Governor
- `LTG16R`: Number of votes for 2016 Republican Lieutenant Governor
- `LTG16O`: Number of votes for 2016 other party's Lieutenant Governor
- `LTG20D`: Number of votes for 2020 Democratic Lieutenant Governor
- `LTG20R`: Number of votes for 2020 Republican Lieutenant Governor
- `LTG20O`: Number of votes for 2020 other party's Lieutenant Governor
- `PRE16D`: Number of votes for 2016 Democratic President
- `PRE16O`: Number of votes for 2016 other party's President
- `PRE16R`: Number of votes for 2016 Republican President
- `PRE20D`: Number of votes for 2020 Democratic President
- `PRE20R`: Number of votes for 2020 Republican President
- `PRE20O`: Number of votes for 2020 other party's President
- `SOS18D`: Number of votes for 2018 Democratic Secretary of State
- `SOS18R`: Number of votes for 2018 Republican Secretary of State
- `SOS18O`: Number of votes for 2018 other party's Secretary of State
- `SOS16D`: Number of votes for 2016 Democratic Secretary of State
- `SOS16R`: Number of votes for 2016 Republican Secretary of State
- `SOS16O`: Number of votes for 2016 other party's Secretary of State
- `SOS20D`: Number of votes for 2020 Democratic Secretary of State
- `SOS20R`: Number of votes for 2020 Republican Secretary of State
- `SOS20O`: Number of votes for 2020 other party's Secretary of State
- `TRE16D`: Number of votes for 2016 Democratic Treasurer
- `TRE16O`: Number of votes for 2016 Republican Treasurer
- `TRE16R`: Number of votes for 2016 other party's Treasurer
- `TRE20D`: Number of votes for 2020 Democratic Treasurer
- `TRE20O`: Number of votes for 2020 Republican Treasurer
- `TRE20R`: Number of votes for 2020 other party's Treasurer
- `USS16D`: Number of votes for 2016 Democratic senate candidate
- `USS16R`: Number of votes for 2016 Republican senate candidate
- `USS16O`: Number of votes for 2016 other party's senate candidate
- `USS20D`: Number of votes for 2020 Democratic senate candidate
- `USS20R`: Number of votes for 2020 Republican senate candidate
- `USS20O`: Number of votes for 2020 other party's senate candidate
