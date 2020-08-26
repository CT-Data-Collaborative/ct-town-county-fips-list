# Connecticut Town to County Crosswalk

The `ct-town-county-fips-list.csv` file contains a crosswalk of all 169 towns in Connecticut,
with FIPS codes (GeoIDs), and their respective counties.

|Town|County|FIPS
|--|--|--|
|Andover|Tolland|0901301080|
|Ansonia|New Haven|0900901220|
|Ashford|Windham|0901501430|
|Avon|Hartford|0900302060|
|Barkhamsted|Litchfield|0900502760|

To prevent Excel from transforming FIPS codes to numbers automatically (which leads to missing leading 0s), do the following:

1. Open Excel, New workbook
1. Go to File > Import > CSV file
1. Choose file, and select "text" as type of FIPS

### Source
See county subdivisions (which are towns for Connecticut) on TIGER: https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2019&layergroup=County+Subdivisions

### License
Released under MIT license. Feel free to use for any project.