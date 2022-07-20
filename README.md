# HydroCerrado
Daniel Althoff*, Lineu Neiva Rodrigues, Demetrius David da Silva

## Short introduction
The HydroCerrado is a regional-sample data set for catchments within the Cerrado biome.
The data set was compiled by <a href='[https://disc.gsfc.nasa.gov/datasets/](https://doi.org/10.1016/j.envsoft.2022.105315)' target='blank'>Althoff et al. (2022)</a> and includes data from gauge stations, catchment boundaries, daily streamflow series, daily time series of meteorological forcing (precipitation and reference evapotranspiration), and catchment attributes.

### Meteorological forcing
The data set covers the period from 2000-06-01 to 2014-12-31 for catchments with > 5 years equivalent of observed data.
Daily time series are catchment averages for precipitation and reference evapotranspiration products:
- Integrated Multi-SatellitE Retrievals for Global Precipitation Measurement (IMERG) (Huffman et al., 2019b, 2019a)
- Gridded reference evapotranspiration for Brazil based on machine learning (ETo-Brazil) (Althoff et al., 2020a, 2020b)

### Catchment attributes
The catchment attributes are related to:
- Topography (area, mean elevation, and mean slope)
- Climate indices (mean annual precipitation, mean annual evapotranspiration, timing of precipitation index, and aridity index)
- Soil characteristics (clay content, silt content, sand content, organic carbon content, and bulk density)
- Land cover characteristics (forest formation, forest plantation, savanna formation, grassland, pasture, crop, urban infrastructure, river and lake, and wetland fractions)

Topography indices are derived from the Shuttle Radar Topography Mission (SRTM) digital elevation model at 3 arc-seconds (Earth Resources Observation And Science Center, 2017). The climate indices are derived from the precipitation and reference evapotranspiration time series. Soil characteristics are derived from the SoilGrids (Hengl et al., 2017) for the top 2.0 m soil layer. The land cover characteristics are derived from the MapBiomas (MapBiomas, 2020). The "crop" land cover consists of the sum of annual and perennial crop, semi-perennial crops and mosaic of agriculture and pasture.

## Runoff time series simulation at ottobasins
The data set also includes the daily streamflow time series (2003-2019) simulated by Althoff et al. (2021) for all level 5 ottobasins within or intersecting the Cerrado.\
*The Otto Pfafstetter classification is adopted in Brazil for the hierarchical classification of hydrologic units consisting of basins and interbasins (Furnans and Olivera, 2001).*\
Even though some ottobasins characterize as interbasins, the simulated streamflow series is an approximation of their discharge contribution to the higher level basins they belong to.\
(..insert ottobasins figure..)

# Related publications

Althoff, D., Rodrigues, L.N., Silva, D.D. da, 2022. Predicting runoff series in ungauged basins of the Brazilian Cerrado biome. Environmental Modelling & Software 149, 105315. https://doi.org/10.1016/j.envsoft.2022.105315

Althoff, D., Rodrigues, L.N. & Silva, D.D. 2021. Assessment of water availability vulnerability in the Cerrado. Applied Water Science 11, 176. https://doi.org/10.1007/s13201-021-01521-2

Althoff, D., Rodrigues, L.N., Silva, D.D. da, 2021. Addressing hydrological modeling in watersheds under land cover change with deep learning. Advances in Water Resources 154, 103965. https://doi.org/10.1016/j.advwatres.2021.103965


# References
Althoff, D., Dias, S.H.B., Filgueiras, R., Rodrigues, L.N., 2020a. ETo-Brazil: A Daily Gridded Reference Evapotranspiration Data Set for Brazil - Repository. Mendeley Data V3. https://doi.org/10.17632/sstjw74ryh.3

Althoff, D., Dias, S.H.B., Filgueiras, R., Rodrigues, L.N., 2020b. ETo‐Brazil: A Daily Gridded Reference Evapotranspiration Data Set for Brazil (2000–2018). Water Resour. Res. 56. https://doi.org/10.1029/2020WR027562

Althoff, D., Rodrigues, L.N., Silva, D.D. da, 2022. Predicting runoff series in ungauged basins of the Brazilian Cerrado biome. Environmental Modelling & Software 149, 105315. https://doi.org/10.1016/j.envsoft.2022.105315

Earth Resources Observation And Science Center, 2017. Shuttle Radar Topography Mission (SRTM) Void Filled. https://doi.org/10.5066/f7f76b1x

Furnans, J., Olivera, F., 2001. Watershed Topology: The Pfafstetter System, in: 2001 User Conference Proceedings. Presented at the 21st Annual Esri International User Conference.

Hengl, T., Jesus, J.M. de, Heuvelink, G.B.M., Gonzalez, M.R., Kilibarda, M., Blagotić, A., Shangguan, W., Wright, M.N., Geng, X., Bauer-Marschallinger, B., Guevara, M.A., Vargas, R., MacMillan, R.A., Batjes, N.H., Leenaars, J.G.B., Ribeiro, E., Wheeler, I., Mantel, S., Kempen, B., 2017. SoilGrids250m: Global gridded soil information based on machine learning. PLoS One 12, e0169748. https://doi.org/10.1371/journal.pone.0169748

Huffman, G.J., Bolvin, D.T., Braithwaite, D., Hsu, K., Joyce, R., Kidd, C., Nelkin, E.J., Sorooshian, S., Tan, J., Xie, P., 2019a. Integrated Multi-satellitE Retrievals for GPM (IMERG) (No. Version 06), Algorithm Theoretical Basis Document. Natioanl Aeronautics and Space Administration.

Huffman, G.J., Stocker, E.F., Bolvin, D.T., Nelkin, E.J., Tan, J., 2019b. GPM IMERG Final Precipitation L3 1 day 0.1 degree x 0.1 degree V06 (No. Edited by Andrey Savtchenko). Goddard Earth Sciences Data and Information Services Center (GES DISC), Greenbelt, MD.

MapBiomas, 2020. Projeto de Mapeamento Anual da Cobertura e Uso do Solo do Brasil [In English: Brazilian Annual Land Use and Land Cover Mapping Project] [WWW Document]. MapBiomas V41. URL http://mapbiomas.org/

