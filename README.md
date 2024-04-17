[![devnet-bundle-snapshot](https://github.com/conterra/mapapps-layer-buildingscene/actions/workflows/devnet-bundle-snapshot.yml/badge.svg)](https://github.com/conterra/mapapps-layer-buildingscene/actions/workflows/devnet-bundle-snapshot.yml)
![Static Badge](https://img.shields.io/badge/tested_for_map.apps-4.17.0-%20?labelColor=%233E464F&color=%232FC050)
# Buildingscene Layer

This bundle adds the Esri layer type BuildingSceneLayer with map.apps layer type `AGS_BUILDING`.

![Screenshot App](https://github.com/conterra/mapapps-layer-buildingscene/blob/master/screenshot.JPG)

## Sample App
https://demos.conterra.de/mapapps/resources/apps/downloads_buildingscenelayer/index.html?lang=de

## Installation Guide
**Requirement: map.apps 4.12.0**

## Quick start

Clone this project and ensure that you have all required dependencies installed correctly (see [Documentation](https://docs.conterra.de/en/mapapps/latest/developersguide/getting-started/set-up-development-environment.html)).

Then run the following commands from the project root directory to start a local development server:

```bash
# install all required node modules
$ mvn initialize

# start dev server
$ mvn compile -Denv=dev -Pinclude-mapapps-deps

# run unit tests
$ mvn test -P run-js-tests,include-mapapps-deps
```
