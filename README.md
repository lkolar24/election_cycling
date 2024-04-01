# Data from *Election Cycling* 

Bike infrastructure and election data are messy, decentralized, and difficult. Being passionate about both data science and these subjects, one contribution I hope to make is allowing for easier use and analysis of cycling and elections. Included in this repository are publicly available, finalized data sets. Additionally, each `.Rmd` file, I include code for recreating my analyses and figures. 

Importantly, these draw on many underlying data sources. These are cited in my senior thesis, but I also include these in individual data set descriptions (see the `descriptions` folder). Below are the data sets included by chapter and their purpose.

Though my full code is not included, I am working on turning many of my important functions - including functions for computing infrastructure walksheds, longitudinal precinct joins, population-weighted block group feature projection onto precincts, and more - into a standalone `R` package. In the meantime, you can reach me at <lukekolar@college.harvard.edu> for my existing (messier) version of these.

### Portland: *Electoral bikelash*

| Data set name  | Description |
| ------------- | ------------- |
| `PDX_all` | Final data set for regressions, with all variables (including many not used in final analysis) and shapefiles for 78 precincts |
| `PDX_protected_lanes`  | Shapefiles for protected lanes constructuted between 2016 and 2020, with links to Google Street View before/after images |
| `PDX_roads` | Street network shapefiles, for visualization |
| `PDX_walksheds` | 15-min. walkshed shapefiles, for visualization |
| `PDX_gent_index_2016` | Portland gentrification index from 2018 study, for visualization |

### Seattle: *Bike lane heuristics*

| Data set name  | Description |
| ------------- | ------------- |
| `SEA_elections_odd` | Final data set for odd-year precinct regressions, with all variables and shapefiles for 833 precincts |
| `SEA_elections_even` | Same as above, but for even-year precinct regressions (815 precincts) |
| `SEA_protected_lanes` | Shapefiles for protected lanes constructuted between 2016 and 2020, with links to Google Street View before/during/after images, and links to validation Internet sources |
| `SEA_walksheds` | 15-min. walkshed shapefiles, for visualization |
| `SEA_boundary` | Seattle boundary, for visualization |



### Manhattan: *Biking to the polls*

| Data set name  | Description |
| ------------- | ------------- |
| `NYC_turnout_all` | Final data set for precinct turnout regressions, with all variables and shapefiles for 775 precincts |
| `NYC_citi_station_ids` | Citi Bike station names, coordinates, and implementation in 2014-2018 period |
| `NYC_citi_2014`,... | Citi Bike rides for 2014 (years through 2018 included) |
| `NYC_weather` | Oct.-Nov. weather in New York City for 2014-2018 |
| `NYC_citi_eday_comparison` | Data with Citi Bike Election Day station volume, proportion to Oct.-Nov. annual average, and more |
| `NYC_boundary` | Manhattan boundary, for visualization |
| `NYC_polling_2018` | Cleaned New York City polling places, 2018 |
| `NYC_citi_2018_eday_distances` | Citi Bike station treatments relating to polling place proximity |
| `NYC_combined_ids_polling` | Citi Bike stations and polling places, for visualization |
