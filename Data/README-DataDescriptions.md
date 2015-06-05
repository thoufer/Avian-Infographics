**PopulationEstimates.csv**

- *Columns 1-2*: Species common name and four letter abbreviation (spp_abbrev: amwi = american wigeon, nopi = northern pintail, scau = scaup spp., rndu = ring-necked duck, pond = natural and artificial wetlands >6" in depth and >33 sqft in area)
- *Column 3*: yr = year of survey
- *Column 4*: stratum = survey stratum (see BackgroundMaterials and/or Shapefiles folders for map and spatial data); the survey consists of 70 strata, numbered between 1 and 77; population estimates are included for the 52 strata in the "traditional survey area" (strata 1-18,20-50,75-77).
- *Columns 5-6*: popn_est = Estimated number of ducks (or ponds) for each species-stratum combination and its se_popn_est = estimated standard error.

**segmentData.csv**

- *Columns 1-3*:  mo, day, yr = month, day, and year that segment was surveyed
- *Columns 4-6*: stratum, transect, and segment surveyed (##-##-## with stratum-transect-segment numbers represents a unique segment code). The survey consists of 70 strata, numbered between 1 and 77.  Not all strata, transects, and segments have been surveyed in every year since 1974. The "eastern survey" was begun in 1990 and includes eighteen strata: 51-59,62-70.
- *Column 7*: species = four letter alpha code for species (amwi = american wigeon, nopi = northern pintail, scau = scaup spp., rndu = ring-necked duck, pond = natural and artificial wetlands >6" in depth and >33 sqft in area)
- *Columns 8-9*: segment counts with total = all ducks of species counted on segment and pairs = number of indicated pairs (male+female and single males)
