# qgis-street-address-parser


A QGIS plugin to parse street addresses into their component parts using a deep learning model from deepparse.org.

 **Work in progress.**

Source code for the REST API is available [here.](https://github.com/tamos/qgis-street-address-parser-api)

As of writing (October 2021) QGIS doesn't yet have a neat way to use external python libraries. To use this plugin, you will need to clone the API repository linked above and follow the steps in the README to run a local web server.

Roadmap:

  - Find a way to neatly integrate the parser into the plugin itself while keeping install process transparent and simple on users' machines (pipx?)
