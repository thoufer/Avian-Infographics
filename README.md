## Avian Info-graphics Challenge
# Background
Every spring since 1955, waterfowl biologists gear up to conduct the Waterfowl Breeding Population and Habitat survey, *aka* the "May Survey". The purpose of this survey is to estimate the population sizes of over 20 species of breeding waterfowl, as well as annual habitat conditions, to support the management of waterfowl (ducks, geese, and swans). The results of the survey are reported each year in tables and plots within the [Trends in Duck Breeding Populations](http://www.fws.gov/birds/surveys-and-data/reports-and-publications/population-status.php), and [Waterfowl Status](http://www.fws.gov/birds/surveys-and-data/reports-and-publications/population-status.php) reports.  

A primary driver of waterfowl population trends is the amont of water on the landscape during the breeding season.  This is currently measured from pond counts made by the aerial survey crews in the prairie and parkland areas of the survey.

# Challenge Goals
The relationships between waterfowl populations, environmental conditions, and the landscape are complex and dynamic. But our current approach to displaying these relationships is static, limiting our ability both to explore the survey results to improve our management actions and to communicate the status of waterfowl communities to the conservation-minded public. This challenge seeks to harness your creativity and skills to help us develop dynamic, interactive graphical displays of the survey results, so that scientists in the US Fish & Wildlife Service, our partners in the broader waterfowl management community, and the public can better visualize, explore and understand continental changes in the distribution and abundance of these beautiful and economically important birds.

The challenge is focusing on four species of ducks: northern pintail *Anas acuta*, American wigeon *Anas americana*, scaup (lesser *Aythya affinis* and greater *Aythya marila* are not distinguished), and ring-necked duck *Aythya collaris*. These species have different distributions, responses to environmental conditions, and population trajectories.  There are currently significant concerns about the status of pintails and scaup, while little assessment work has been done to date on wigeon and ring-neck populations.

Displays might include (1) population trajectories over space and time, (2) relationships between abundance, distribution and water conditions, and (3) the relationship among the species (relative changes in abundance and distribution) that might indicate common or unique factors driving distribution and population change. 

# Data
We are providing several different "types" of data to use in the challenge: 
 
1. 1974-2012 annual population estimates for the four species for each of the mid-continent survey "strata", along with spatial information about the strata. Annual estimates of pond totals for each prairie/parkland stratum in which ponds are counted.
2. Survey segment counts from 1974-2012 for the four species and ponds (the "raw" data used to create the population estimates) for the entire survey area (mid-continent and eastern survey area), along with spatial information about the location of the strata.
	* TotalBirds Column:  This reflects the total number of birds observed on a segemnt.
	* Pairs Column: Observers record social groupings during the survey, and this reflects the number of breeding pairs observed.  A breeding pair is defined as 1 male + 1 female, or 1 single male.  Single males are presumed to have a female on a nest.
	* From 2000 to 2012 counts are weighted by the proportion of the segment actually flown. This is reflected by non-integer counts in the totalBirds, and pairs columns.
	* If a segement for a particular year/stratum/transect does not appear in the table then it was not flown.

3. A link to continental, spatially explicit precipitation data that can provide more extensive information about habitat conditions than the survey-specific pond counts.

The survey consists of 459 transects, which are divided into ~18 mile segments for data collection purposes (prior to GPS technology, spatial information about count location was collected by segment). A pilot-observer (left seat) and observer (right seat) count all waterfowl seen, by species, within 1/8 mile from either side of the survey aircraft, which flies at an altitude of 100 ft and ~90 mi/hr. ([Pilot observations](http://www.flyways.us/status-of-waterfowl/pilot-reports)) For the purpose of population estimation, the transects are divided into strata and supplementary data are used to correct for differences in detection among survey crews. 

Ponds are counted by the right seat observer on 149 transects within 26 of the survey strata.  


**Survey spatial information**:
We have provided 2 shapefiles in ESRI .shp format in the repo that might be of benefit/interest:
1. WBPHS\_Stratum\_boundaries.shp
2. WBPHS\_Segments.shp
The stratum boundaries contains the stratum polygon boundaries for all of the strata surveyed. Both shapefiles are in a Geographic Pojection, NAD83 Dataum.  

**Supplemental environmental data relevant to understanding waterfowl distribution and abundance**:
- Temperature and Precipiation data compiled by researchers from the University of Delaware. Data hosted by [NOAA](http://www.esrl.noaa.gov/psd/data/gridded/data.UDel_AirT_Precip.html) or direcly by the [University of Delaware] (http://climate.geog.udel.edu/~climate/html_pages/download.html)


