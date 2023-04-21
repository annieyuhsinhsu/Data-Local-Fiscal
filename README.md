# Data-Local-Fiscal

## Data: 

1. Master_xx.dta: annual data, decomposing by MSA, top 60 biggest city and their surrounding suburbs

2. IndFin_final_cz_xxx.dta: decadal data, decomposing by CZs, top 100 biggest commuting zones (defined by 1990 Census population)


## File: 2017 S&L Indiv Unit Data File Tech Doc.pdf

1. There are five types of local government: (1) County, (2) City, (3) Town, (4) Special district, and (5) School district.

1.1 Type 2 and Type 3 local governments are multiple-purpose governments.

1.2 City governments might not follow county boundaries.

1.3 OMB defines MSA (Metropolitan Statistical Area), including a central city and surrounding suburbs. It is the economic boundary. (Delineation files)


## File: GOVS_ID_to_FIPS_Place_Codes_2012.xls, GOVS_to_FIPS_Codes_State_&_County_2012.xls

1. Local governments are identified by "id_govs."

1.1 There are two identifications: Fips_code, Govs_code

1.2 Census provides the cross-walk files.

1.3 id_govs: govs_state + govs_type + govs_cnty + govs_place

1.4 Most of the demographic variables (like population) are provided in Fips_code

1.5 Local fiscal data are provided in Govs_code


## File: 2006_classification_manual.pdf

1. Define each fiscal variable and the measurement issues.


## File: methodology_for_summary_tabulations.xls

1. Provide the item code for each variable.


## Data source (Please cite this website for this file): 
1. Fiscal data: https://www2.census.gov/programs-surveys/gov-finances/
2. Delineation files: https://www.census.gov/geographies/reference-files/time-series/demo/metro-micro/delineation-files.html
3. Annual Survey of State and Local Government Finances: https://www.census.gov/programs-surveys/gov-finances/data/historical-data.html
4. Pierson K., Hand M., and Thompson F. (2015). The Government Finance Database: A Common Resource for Quantitative Research in Public Financial Analysis. PLoS ONE doi: 10.1371/journal.pone.0130119: https://willamette.edu/mba/research-impact/public-datasets/index.html
