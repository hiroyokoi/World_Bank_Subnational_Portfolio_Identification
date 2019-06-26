# World Bank Subnational Portfolio Identification


## Motivation
- We don't know the project location.
- Geotag is provided for each project but underutilized.
- Nobody knows geographical precision supplied by geotag.
- In our evaluation on Managing Urban Spatial Growth (MUSG), we focus on spatial issues. Important to understand the - subnational level portfolio.

## Methodology
1. Extract Geolocation ID from the global portfolio and merge them into MUSG portfolio
2. Convert Geolocation ID into place name (state, adm2, adm3,etc.)
3. Visualize subnational portfolio
4. (optional) Correlation with population

## Results
- Total number of project sites in the portfolio is 5,672.
- Geocoding coverage of the portfolio is 70%. (Geocoding coverage of the global portfolio is 24%)
- Average number of project site is 14.
- Top 5 Project Sites are
1. n= 297	: ENVIRONMENTAL SERVICES PROJECT (P130492) in Albania
2. n= 113	: Indonesia Nat'l Slum Upgrading Project (P154782) in Indonesia
3. n= 98	: Agriculture Growth & Land Management (P151469) in Madagascar
4. n= 89	: MUNICIPAL SERVICES IMPROVEMENT 2 (P154464) in Macedonia
5. n= 82	: Bahia Road Rehabilitation and Maintenance (P147272) in Brazil

Admin Boundary	N	%<br>
Total Project Site	5,672	--<br>
State	5,304	93.52%<br>
Admin2	2,376	41.89%<br>
Admin3	764	13.46%<br>
Admin4	199	3.51%<br>
Admin5	16	0.003%<br>

## Lessons
- Geocoding is useful to understand broader engagement with subnational governments.
- Subnational level portfolio identification is replicable and scalable for other major evaluations and CPE because all the scripts were prepared in Python.
- Geocoding is not fit for purpose. The quality of geocoding needs to be validated. MUSG projects normally intervenes with city/neighborhood level, while the geocoding result shows only 13.5% (Admin3) and 3.5% (Admin4). Validation through portfolio analysis is expected.
