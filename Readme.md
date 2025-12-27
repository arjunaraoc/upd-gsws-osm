#osm-utilities

Utilities for OSM updates, gathering and visualising osm statistics
and  Overpass Turbo, JOSM

## Description


## Getting Started

### Dependencies

* Python 3 Jupyter notebook server
* Overpass Turbo query to get osm file.


### Installing

* Just open the relevant notebook file

* preprocess-secretariats.ipynb : cleans up data in secretariats.csv and generates cleanedup file
* cleanup-gsws-osm.ipynb:  updates name and ref information on offices already present on 2025-12-18
* todo-gsws-osm.ipynb: removes data already updated before 2025-12-18
* eval-pmgsy.ipynb: evaluates location accuracy of pmgsy against manually mapped data(only the hq unit or place unit with suffix -1 considered)
* todo-gsws-osm.ipynb: todo list of GSWS considering only node mappings and excluding already present data. Need enhancedment to consider ways also.  GSWS update pending for India OGDL release

* amenities-osm.ipynb: district and mapping type info of amenities meeting a pattern in name
    * viz_osm_stats.ipynb: prepare chlolopleth map for a specific amenity, needs data created using amenities-osm-ipynb
* osmand_ap_stats.ipynb: gather size of OsmAnd Andhra Pradesh file size, going through archived OsmAnd map dowloads page. (http error handling imperfect, but usable)
    * viz_osmand_stats.ipynb: prepares map activity time series data and derived yoy growth data. Input is data created from osmand_ap_stats.ipynb





### Executing program

* Run the notebook: If the output is osm chage file, load .osc file in JOSM and upload to OSM


## Help


## Authors

Contributors names and contact info

Arjuna Rao C with assistance from Chatgpt/ Co pilot


## Version History


* 0.1
    * Initial Release; 18 December 2025
* 0.2
    * Update to support OSM stats, 27 December 2025

## License

This project is licensed under the [MIT] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [Chatgpt](https://chatgpt.com)/ Co pilot

