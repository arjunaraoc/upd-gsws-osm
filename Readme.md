# upd-gsws-osm

Utilities for updating Grama sachivalayam, ward sachivalayam locations on OSM using  secretariat lat long files 
and  Overpass Turbo, JOSM

## Description

In Andhra Pradesh,  village/ward secretariats were launched in 2019, to support administration decentralisation. These offices are housed in panchayat buildings. This project  helps to cleanup existing secretariat location data, add mising data.

## Getting Started

### Dependencies

* Python 3 Jupyter notebook server
* Overpass Turbo query to get osm file.


### Installing

* Just open the relevant notebook file

* preprocess-secretariats.ipynb : cleans up data in secretariats.csv and generates cleanedup file
* cleanup-gsws-osm.ipynb:  updates name and ref information on offices already present on 2025-12-18
* todo-secretariats.ipynb: WIP removes data already updated before 2025-12-18
* add-new-gsws-osm.ipynb: WIP  adds new offices per each selected district, run only once per district.


### Executing program

* Run the notebook: If the output is osm chage file, load .osc file in JOSM and upload to OSM


## Help


## Authors

Contributors names and contact info

Arjuna Rao C with assistance from Chatgpt/ Co pilot


## Version History


* 0.1
    * Initial Release; 18 December 2025

## License

This project is licensed under the [MIT] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [Chatgpt](https://chatgpt.com)/ Co pilot

