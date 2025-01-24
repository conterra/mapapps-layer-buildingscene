⚠️ This bundle is no longer in active development. BuildingSceneLayers are supported by map.apps as of version 4.19.0.
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
