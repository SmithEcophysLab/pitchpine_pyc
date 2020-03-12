# pitchpine_pyc

## general information
This repository houses data from an experiment in Massachusetts examining the 
response of Pitch Pine to pyrogenic carbon (PyC) soil amendments.
The dataset corresponds to the article *Pyrogenic carbon increases pitch pine seedling
frowth, soil moisture retention, and photosynthetic intrinsic water use efficiency in
the field* by Licht and Smith in *Frontiers in Forests and Global Change*. [link to
article to be added following publication]

## authors
Jeff Licht (jefflicht64@gmail.com) and Nick Smith (nick.gregory.smith@gmail.com)

## DOI badge
[![DOI](https://zenodo.org/badge/246387220.svg)](https://zenodo.org/badge/latestdoi/246387220)

## folder descriptions
### /data
This folder contains all of the data files.

## file descriptions
### /data/pitchpine_pyc_biometrics.csv
This file contains stem diameter, plant height, and root length data. The specific
column information is:
- *year*: the year the measurement was taken
- *soil_treatment*: the soil treatment, where *Control* is the untreated control, 
*PyCA* is the soil treated with pyrogenic carbon created from recycled feedstock, and
*PyCF* is the soil treated with pyrogenic carbon created from forest materials 
- *stem_diameter*: the diameter of the main stem at 5 cm height (cm)
- *height*: the height of the tree (cm)
- *root_length*: the length of longest root (cm)

### /data/pitchpine_pyc_foliar_cn_isotopes.csv
This file contains stem circumference, plant height, and root length data. The specific
column information is:
- *individual_id*: a unique identifier for each individual tree
- *year*: the year the measurement was taken
- *soil_treatment*: the soil treatment, where *Control* is the untreated control, 
*PyCA* is the soil treated with pyrogenic carbon created from recycled feedstock, and
*PyCF* is the soil treated with pyrogenic carbon created from forest materials 
- *d13c*: the carbon-13 isotope discrimination value (per mil)
- *d15n*: the nitrogen-15 isotope discrimination value (per mil)
- *c_percent*: percent carbon in leaves (% or [gC/gLeaf * 100])
- *n_percent*: percent nitrogen in leaves (% or [gN/gLeaf * 100])

### /data/pitchpine_pyc_retention.csv
This file contains stem circumference, plant height, and root length data. The specific
column information is:
- *year*: the year the measurement was taken
- *soil_treatment*: the soil treatment, where *Control* is the untreated control, 
*PyCA* is the soil treated with pyrogenic carbon created from recycled feedstock, and
*PyCF* is the soil treated with pyrogenic carbon created from forest materials 
- *retention*: moisture retained by soil during dry down-to-moisten up bench test (unitless; 0-1)

### /data/pitchpine_pyc_soil_nutrients_cec_ph.csv
This file contains soil nutrient, cation exchange capacity (CEC), and pH data. The specific
column information is:
- *year*: the year the measurement was taken
- *soil_treatment*: the soil treatment, where *Control* is the untreated control, 
*PyCA* is the soil treated with pyrogenic carbon created from recycled feedstock, and
*PyCF* is the soil treated with pyrogenic carbon created from forest materials 
- *Ca*: soil calcium (mg kg-1)
- *P*: soil phosphorus (mg kg-1)
- *Mg*: magnesium (mg kg-1)
- *K*: soil potassium (mg kg-1)
- *Al*: soil aluminum (mg kg-1)
- *Zn*: soil zinc (mg kg-1)
- *CEC*: soil cation exchange capacity (meq 100 g-1)
- *pH*: soil pH (-log[H+])

### /data/pitchpine_pyc_foliar_nutrients.csv
This file contains foliar nutrient data. The specific
column information is:
- *year*: the year the measurement was taken
- *soil_treatment*: the soil treatment, where *Control* is the untreated control, 
*PyCA* is the soil treated with pyrogenic carbon created from recycled feedstock, and
*PyCF* is the soil treated with pyrogenic carbon created from forest materials 
- *Ca*: soil calcium (mg kg-1)
- *P*: soil phosphorus (mg kg-1)
- *Mg*: magnesium (mg kg-1)
- *K*: soil potassium (mg kg-1)
- *Al*: soil aluminum (mg kg-1)
- *Zn*: soil zinc (mg kg-1)

### /data/pitchpine_pyc_charcoal_nutrients_cec_ph.csv
This file contains soil nutrient, cation exchange capacity (CEC), and pH data. The specific
column information is:
- *year*: the year the measurement was taken
- *charcoal*: the charcoal type, where 
*PyCA* is the pyrogenic carbon created from recycled feedstock and
*PyCF* is the pyrogenic carbon created from forest materials 
- *Ca*: soil calcium (mg kg-1)
- *P*: soil phosphorus (mg kg-1)
- *Mg*: magnesium (mg kg-1)
- *K*: soil potassium (mg kg-1)
- *Al*: soil aluminum (mg kg-1)
- *Zn*: soil zinc (mg kg-1)
- *CEC*: soil cation exchange capacity (meq 100 g-1)
- *pH*: soil pH (-log[H+])

### /data/pitchpine_pyc_sedge_forest_soil_nutrients_cec_ph.csv
This file contains soil nutrient, cation exchange capacity (CEC), and pH data for sedge meadow soils. The specific
column information is:
- *year*: the year the measurement was taken
- *soil_treatment*: the charcoal type, where 
*SM* is the untreated sedge meadow soil and
*SMPyCA* is the sedge meadow soil treated with pyrogenic carbon created from recycled feedstock
- *Ca*: soil calcium (mg kg-1)
- *P*: soil phosphorus (mg kg-1)
- *Mg*: magnesium (mg kg-1)
- *K*: soil potassium (mg kg-1)
- *Al*: soil aluminum (mg kg-1)
- *Zn*: soil zinc (mg kg-1)
- *CEC*: soil cation exchange capacity (meq 100 g-1)
- *pH*: soil pH (-log[H+])


