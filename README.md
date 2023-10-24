# Arbovirus overview
In progress

## Dengue
### Filename
Data source: [Istituto Superiore di Sanità (ISS)](https://www.epicentro.iss.it/arbovirosi/dashboard) <br>
**Directory:**  arbovirus/dengue<br>
**Filename:** dengue-ita-yyyy.csv <br>


| Field                 | Format                       |Description                      
|-----------------------------|-----------------------------------|-------------------------------|
| **data**      | String (YYYY-MM-DD) | 	Bulletin date  |
| **new_cases**      | Numeric | Number of new weekly reported cases of dengue |
| **total_cases**      | Numeric | Total number of reported cases of dengue	  |
| **new_deaths**      | Numeric | 	Number of new weekly reported deaths of dengue  |
| **total_deaths**      | Numeric |  Total number of reported cases of dengue	  |
| **male**      | Numeric |  	Percentage of weekly dengue cases reported in males  |
| **female**      | Numeric | Percentage of weekly dengue cases reported in females 	  |
| **median_age**      | Numeric |  Median weekly age of people affected by dengue	  |
| **autochthonous**      | Numeric |  Number of weekly dengue cases that are locally transmitted	  |
| **imported**      | Numeric |  Number of weekly dengue cases that are imported (acquired from outside the local area)	  |


**Directory:**  arbovirus/dengue<br>
**Filename:** dengue-ita-age-yyyy.csv <br>

| Field                 | Format                       |Description                      
|-----------------------------|-----------------------------------|-------------------------------|
| **data**      | String (YYYY-MM-DD) | 	Bulletin date  |
| **age**      | String | 	Age of individuals affected by dengue. Age groups: `0-9`, `10-19`, `20-29`, `30-39`, `40-49`, `50-59`, `60+`  |
| **new_cases**      | Numeric | Number of new weekly reported cases of dengue |
| **total_cases**      | Numeric | Total number of reported cases of dengue	  |
| **male**      | Numeric |  	Percentage of weekly dengue cases reported in males  |
| **female**      | Numeric | Percentage of weekly dengue cases reported in females 	  |
| **incidence**      | Numeric |  Weekly incidence rate of dengue cases	  |



**Directory:**  arbovirus/dengue<br>
**Filename:** dengue-ita-location-exposure-yyyy.csv <br>

| Field                 | Format                       |Description                      
|-----------------------------|-----------------------------------|-------------------------------|
| **data**      | String (YYYY-MM-DD) | 	Bulletin date  |
| **location**      | String |  Information on the geographic location or region associated with imported dengue cases	  |
| **percent_cases**      | Numeric |  Weekly percentage of dengue cases in relation to the total number of cases per location |


**Directory:**  Data/Europe/Italy/<br>
**Filename:** dengue-ita-regions-yyyy.csv <br>
| Field                 | Format                       |Description                      
|-----------------------------|-----------------------------------|-------------------------------|
| **data**      | String (YYYY-MM-DD) | 	Bulletin date  |
| **code_region**      | String  | 	Alphanumeric code to identify a specific geographic region where cases on dengue are reported  |
| **name_region**      | String  | 	Name of the geographic region where cases on dengue are reported  |
| **lat**      | String  | Latitude coordinate associated with the region where cases on dengue are reported	  |
| **lon**      | String  | Longitude coordinate associated with the region where cases on dengue are reported	  |
| **new_cases**      | Numeric | Number of new weekly reported cases of dengue |
| **total_cases**      | Numeric | Total number of reported cases of dengue	  |


**Directory:**  arbovirus/dengue<br>
**Filename:** dengue-ita-summary-cases.csv <br>
| Field                 | Format                       |Description                      
|-----------------------------|-----------------------------------|-------------------------------|
| **year**      | String | 	Year of reported cases of dengue  |
| **month**      | String | 	Month of reported cases of dengue  |
| **cases**      | Numeric | 	Total number of reported cases of dengue  |
| **autochthonous**      | Numeric |  Number of weekly dengue cases that are locally transmitted	  |
| **imported**      | Numeric |  Number of weekly dengue cases that are imported (acquired from outside the local area)	  |

**Directory:**  arbovirus/dengue<br>
**Filename:** dengue-ita-summary-cases-regions.csv <br>
| Field                 | Format                       |Description                      
|-----------------------------|-----------------------------------|-------------------------------|
| **year**      | String | 	Year of reported cases of dengue  |
| **code_region**      | String  | 	Alphanumeric code to identify a specific geographic region where cases on dengue are reported  |
| **name_region**      | String  | 	Name of the geographic region where cases on dengue are reported  |
| **lat**      | String  | Latitude coordinate associated with the region where cases on dengue are reported	  |
| **lon**      | String  | Longitude coordinate associated with the region where cases on dengue are reported	  |
| **cases**      | Numeric | 	Total number of reported cases of dengue  |


## West Nile

All data are available at the link: https://github.com/fbranda/west-nile






