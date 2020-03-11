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

## folder descriptions
### /data
This folder contains all of the data files.

## file descriptions
### /data/memorial_biometrics.csv
This file contains stem diameter, plant height, and root length data. The specific
column information is:
- *year*: the year the measurement was taken
- *soil_treatment*: the soil treatment, where *Control* is the untreated control, 
*PyCA* is the soil treated with pyrogenic carbon created from recycled feedstock, and
*PyCF* is the soil treated with pyrogenic carbon created from forest materials 
- *stem_diameter*: the diameter of the main stem at 5 cm height (cm)
- *height*: the height of the tree (cm)
- *root_length*: the length of longest root (cm)

### /data/memorial_foliar.csv
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

### /data/memorial_retention.csv
This file contains stem circumference, plant height, and root length data. The specific
column information is:
- *year*: the year the measurement was taken
- *soil_treatment*: the soil treatment, where *Control* is the untreated control, 
*PyCA* is the soil treated with pyrogenic carbon created from recycled feedstock, and
*PyCF* is the soil treated with pyrogenic carbon created from forest materials 
- *retention*: moisture retained by soil during dry down-to-moisten up bench test (unitless; 0-1)
