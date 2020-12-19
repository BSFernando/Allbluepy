Allbluepy returns oceanic information such as region, economic zone and provinces of coordinates closest to input values.

------

Install: pip install allbluepy==0.2.0

------

Example:

	>>>import allbluepy
	>>>exem = allbluepy.Allblue()
	>>>exem.buscar(-70, 45, 3)
  
	Código província                                      NWCS
	Província           Coastal - NW Atlantic Shelves Province
	x                                                      -70 <-coord mais próxima encontrada
	y                                                       44 <-coord mais próxima encontrada
  
------

Database made from extraction of vertices from shapefile files:

1 Downloaded files: 'Flanders Marine Institute (2020): MarineRegions.org. Disponível online em www.marineregions.org . Consultado em 2020-12-08.';

<img src="https://github.com/BSFernando/Allblue/blob/main/jpeg/0site.jpg" alt="alt text" width="600px">

2 Decrease in number of vertices in each polygon;

<img src="https://github.com/BSFernando/Allblue/blob/main/jpeg/1snap.jpg" alt="alt text" width="600px">

3 Vertices extraction;

<img src="https://github.com/BSFernando/Allblue/blob/main/jpeg/2vert.jpg" alt="alt text" width="600px">
<img src="https://github.com/BSFernando/Allblue/blob/main/jpeg/3pontos.jpg" alt="alt text" width="600px">

4 Calculation of coordinates and selection of interest values in attribute table;

<img src="https://github.com/BSFernando/Allblue/blob/main/jpeg/4coord.jpg" alt="alt text" width="600px">

5 Attribute table saved in csv format.
