## Multimodal public transport network model - level 0 - baseline model
## Requirements
#### Data
To create this model, it is necessary to have a General Transit Feed Specification (GTFS) dataset. Additionally, you need a street network model and the polygons of the cities or regions you are working with. 

In the case of this repository, we're using the Västra Götaland Region GTFS dataset:

- [Västra Götaland Region GTFS](https://www.trafiklab.se/api/trafiklab-apis/gtfs-regional/static/)

To have access to this dataset, it is necessary to [register](https://developer.trafiklab.se/user/register) on the website, create a project, and generate API keys for the target dataset.

For the city polygons and the street network model, we are extracting information from  [Open Street Map (OSM)](https://www.openstreetmap.org/).

#### Packages

- [pandas](https://pandas.pydata.org/) - _version 2.2.1_
- [geopandas](https://geopandas.org/en/stable/) - _version 0.14.13_
- [numpy](https://numpy.org/) - _version 1.23.1_
- [shapely](https://pypi.org/project/Shapely/) - _version 1.8.2_
- [osmnx](https://osmnx.readthedocs.io/en/stable/)- _version 1.2.2_


## Soft Requirements

#### Packages

- [SQLAlchemy](https://www.sqlalchemy.org/) - _version 1.4.40_

## Citation

#### GTFS dataset

- Trafiklab. (2022). Static GTFS Regional dataset [Data set]. In Tafiklab Static data. https://www.trafiklab.se/api/trafiklab-apis/gtfs-regional/static/

