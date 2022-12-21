# Colouring Cities Core Platform

> Work in progress

The core implementation of the [Colouring Cities](https://github.com/colouring-cities) platform.

Colouring Cities is a web-based citizen social science project designed to help address these questions by crowd-sourcing and visualising various categories of information on a city’s buildings.

See [colouring-london](https://github.com/colouring-cities/colouring-london/) 
for the reference implementation.

## Structure

This repository will contain open-source code for the project which:

- stores building footprint polygons and source metadata
- allows site users to record building attribute data
- serves map tiles rendered from collected data
- allows site visitors to download the collected building attribute data

Building attribute data collected as part of the project will be made available
for download under a liberal open data license
([ODbL](https://opendatacommons.org/licenses/odbl/1.0/)).

## Setup and run

#### Test the application:

You can try out the Colouring Cities application by setting up your own development environment, which includes the option to load test data from OpenStreetMaps (OSM). See [docs/setup-dev-environment](docs/setup-dev-environment.md).
  
_Last updated March 2022_

#### Configuring the application:

You can customise the appearance and settings for the Colouring Cities application, for example by changing the Colouring {City Name} or changing the initial map location. This is done through JSON config files. For more, see [docs/configure-your-environment](docs/configure-your-environment.md).
  
_Last updated December 2022_

#### Create a production version of the application:

We also have documentation on setting up a production environment here: [docs/setup-production-environment](docs/setup-production-environment.md).
  
_Last updated December 2021_

**Note:** There are additional useful documentation within the `/docs` folder.

## Acknowledgements

Colouring Cities was set up at the Centre for Advanced Spatial
Analysis (CASA), University College London and is now based at The Alan Turing Institute.
Ordnance Survey is providing building footprints required to collect the data,
facilitated by the Greater London Authority (GLA), and giving access to its API
and technical support.

## License

    Colouring Cities
    Copyright (C) 2018-2022 Tom Russell and Colouring Cities contributors

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program. If not, see <http://www.gnu.org/licenses/>.