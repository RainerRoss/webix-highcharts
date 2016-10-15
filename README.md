# webix-highcharts

features :
----------

* property 'autoreset' (default: true) : removes automatically ('onBeforeLoad') the data of the datastore to avoid adding series  in case of reloading.
* a hacked setParams() method which currently only allows to set X axis limits

new functions added:

setTitle, setCategories, addPlotLine, removePlotLine

problems:
---------

* the highcharts library needs to be loaded beforehand.
* strange (random) resizing problems ( at least under chrome 44 )


