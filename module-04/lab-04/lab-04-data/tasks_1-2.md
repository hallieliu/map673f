# Lab 04: Tasks 1 + 2

** DATASETS: **
Pasha Center Locations (2016),
County Population (2009), Kenyan Counties

** Data Source: **
[Kenya's open data portal](https://www.opendata.go.ke/), [Open Africa](https://africaopendata.org/dataset/kenya-counties-shapefile)

** Why make this product? **
* To visually identify access to the internet

** What do I want to get from this product? **
* A tool for locating Pasha Centers, and to visualize how many Kenyans have access to public internet use
* A map that is visually pleasing and understandable

** What do I want to provide to users of this product?**
* A map that works
* An interface that is useable and requires little explanation
* Popup with data summary

** Content Requirements **

* Population density as areal data by county
 * choropleth 
 * households per sq km 
* Pasha locations as points 
* Popup for county summarizing 
 * total no. households,
 * no. households per sq km 
 * no. households per Pasha Center     
* Basemap that includes county boundaries
* Legend


** Functional Specifications **

* Bind county location geoJSON to pop density from CSV file

* Load Pasha data dynamically from CSV file

* Data layer for population density

* Data layer for each energy source

* Data layers will be drawn to map

* Popup information will be attached to each symbol and available on click or hover (energy data popups include bar/graphs??)

* Legend and toggle options will be visually combined to one unit
