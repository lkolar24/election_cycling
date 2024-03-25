# Data: Portland

See thesis for abbreviations not otherwise defined. Note that earlier versions included many more variables; I decided to keep those I thought would be useful. Sources are listed here; more information and/or hyperlinks can be found in thesis.

### `PDX_all`

| variable  | description | orig. source(s) |
| --------- | ----------- | ----- |
| `precinctid` | - | - |
| `geometry` | - | - | 
| `cast_votes_2016` | - | - | 
| `cast_votes_2020` | - | - | 
| `wheeler_perc_2016` | - | - | 
| `wheeler_perc_2020` | - | - | 
| `wheeler_change` | - | - | 
| `t1_prtct_all` | - | - | 
| `t1_paint_all` | - | - | 
| `t1_prtct_type1` | - | - | 
| `t1_prtct_type2` | - | - | 
| `t1_prtct_type1_2016` | - | - | 
| `t1_prtct_type1_2017` | - | - | 
| `t1_prtct_type1_2018` | - | - |
| `t1_prtct_type1_2019` | - | - |
| `t1_prtct_type1_2020` | - | - |
| `t1_prtct_type2_2016` | - | - |
| `t1_prtct_type2_2017` | - | - |
| `t1_prtct_type2_2018` | - | - |
| `t1_prtct_type2_2019` | - | - |
| `t1_prtct_type2_2020` | - | - | 
| `t2_prtct_all` | - | - |
| `t2_prtct_type1` | - | - |
| `t2_prtct_type2` | - | - | 
| `t2_prtct_type1_2016` | - | - |
| `t2_prtct_type1_2017` | - | - | 
| `t2_prtct_type1_2018` | - | - |
| `t2_prtct_type1_2019` | - | - |
| `t2_prtct_type1_2020` | - | - |
| `t2_prtct_type2_2016` | - | - |
| `t2_prtct_type2_2017` | - | - |
| `t2_prtct_type2_2018` | - | - |
| `t2_prtct_type2_2019` | - | - |
| `t2_prtct_type2_2020` | - | - | 
| `pop_2010` | - | - |
| `gent_area` | - | - |
| `pre_gent_area` | - | - | 
| `bgp_perc_auto` | - | - |
| `bgp_median_age` | - | - |
| `bgp_median_inc` | - | - |
| `pop_density_2010` | - | - |
| `area_miles` | - | - |

### `PDX_protected_lanes`

| variable  | description | orig. source(s) |
| --------- | ----------- | ----- |
| `name` | - | - |
| `geometry` | - | - |
| `type` | - | - |
| `year_built` | - | - | 
| `infra_before` | - | - | 
| `before_image` | - | - |
| `before_image_year` | - | - |
| `after_image` | - | - |
| `after_image_year` | - | - |

### `PDX_walksheds`

| variable  | description | orig. source(s) |
| --------- | ----------- | ----- |
| `name` | - | - |
| `geometry` | - | - |
| `type` | - | - |
| `year_built` | - | - | 
| `infra_before` | - | - | 
| `walk_15` | - | - | 

### `PDX_roads`

| variable  | description | orig. source(s) |
| --------- | ----------- | ----- |
| `geometry` | Portland road shape; all joined by geography | Census GIS via `tinytiger` package |

### `PDX_gent_index_2016`

| variable  | description | orig. source(s) |
| --------- | ----------- | ----- |
| `tract` | 2010 Census tract ID | Census via `censable` package |
| `geometry` | 2010 Census tract shapefile | Census GIS via `censable` package |
| `gent_index` | Gentrification index using data pre-2016 demographic data | Portland 2018 gentrification study |
