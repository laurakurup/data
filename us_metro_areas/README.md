# U.S. Metropolitan and Micropolitan Area CBSA and FIPS codes (2013)

**Source:** https://www.census.gov/population/metro/data/def.html

**Core Based Statistical Areas (CBSAs)** consist of the county or counties or equivalent entities associated with at least one core (urbanized area or urban cluster) of at least 10,000 population, plus adjacent counties having a high degree of social and economic integration with the core as measured through commuting ties with the counties associated with the core. ([U.S. Census](https://www.census.gov/geo/reference/gtc/gtc_cbsa.html))

**Federal Information Processing Standard (FIPS)** codes uniquely identify counties and county equivalents in the United States, certain U.S. possessions, and certain freely associated states. ([Wikipedia: FIPS county code](https://en.wikipedia.org/wiki/FIPS_county_code))


## Fields in this dataset:

+ **cbsa_code**			    – the CBSA code for the statistical area

+ **cbsa_name**			    – the name of the statistical area (cities and state)

+ **metro_micro**			    – one of two values:

  + *micropolitan* areas have a population between 10,000 and 50,000

  + *metropolitan* areas have a population greater than 50,000

+ **city_name**			    – the name of the city within the statistical area 

+ **state_fips**			    – the FIPS code of the state

+ **place_fips**			    – the FIPS code of the city

**_There can be mulitple cities within one statistical area.  For example:_**

| cbsa_code	| cbsa_name	| metro_micro	| city_name	| state_fips	| place_fips |
| -------- | --------	| --------	| --------	| --------	| -------- |
| 10380	| Aguadilla-Isabela, PR	| metropolitan	| Aguadilla	| 72	| 745 |
| 10380	| Aguadilla-Isabela, PR	| metropolitan	| Isabela	| 72	| 36478 |



## More Information

From the U.S. Census:
+ [2010 FIPS Codes for Counties and County Equivalent Entities](https://www.census.gov/geo/reference/codes/cou.html)

+ The inventory, names, and codes for counties and equivalent areas change periodically. Please review [Substantial Changes to Counties and County Equivalent Entities: 1970-Present](https://www.census.gov/geo/reference/county-changes.html).
