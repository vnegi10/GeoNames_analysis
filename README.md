# GeoNames_notebook.jl

This repository contains a Pluto notebook to inspect data obtained from 
[GeoNames.](https://download.geonames.org/export/dump/). 

This work is licensed under a Creative Commons Attribution 4.0 License,
see [here.](https://creativecommons.org/licenses/by/4.0/) The data is provided
"as is" without warranty or any representation of accuracy, timeliness or
completeness. The data format is tab-delimited text in utf8 encoding.

**Files are used as input for the [Weather.jl](https://github.com/vnegi10/Weather.jl)
package.**

## Files

cities500.zip --> all cities with a population > 500
cities15000.zip --> all cities with a population > 15000

## Data extracted

Following fields are read from the main 'geoname' table:

- asciiname: name of geographical point in plain ascii characters, varchar(200)
- latitude: latitude in decimal degrees (wgs84)
- longitude: longitude in decimal degrees (wgs84)
- timezone: the iana timezone id varchar(40)