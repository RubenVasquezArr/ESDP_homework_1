# ESDP_homework_1

The idea of this project is to download ERA5 meteorological data, understand the API, process the information, and use this information to use world grids.

For this analisys, temperature information of the ERA5 model was obtained using the Copernicus API, wich was then used to understand nc files, plot in diferent ways, and finally interpolated into a HEALPIX grid and Ubers H3 hexagonal grid. 

The order is as follows:

-[Load Era 5 Data](https://github.com/RubenVasquezArr/ESDP_homework_1/blob/main/load_era5.ipynb)

-[Data exploration](https://github.com/RubenVasquezArr/ESDP_homework_1/blob/main/data_exploration.ipynb)

-[HEALpix grid inteprolation](https://github.com/RubenVasquezArr/ESDP_homework_1/blob/main/HEALpix_grid_interpolation.ipynb)

-[Uber's H3 grid interpolation](https://github.com/RubenVasquezArr/ESDP_homework_1/blob/main/H3_grid_interpolaton.ipynb)
 


 
### Sources

Copernicus data download instructions: https://cds.climate.copernicus.eu/api-how-to

HEALpix library for python: https://healpy.readthedocs.io/en/latest/

H3 Information and library: https://h3geo.org/