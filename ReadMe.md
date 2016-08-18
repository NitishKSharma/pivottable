[![npm](http://nicolas.kruchten.com/pivottable/images/npm.svg)](https://www.npmjs.com/package/pivottable) [![cdnjs](http://nicolas.kruchten.com/pivottable/images/cdnjs.svg)](https://cdnjs.com/libraries/pivottable) [![tests](http://nicolas.kruchten.com/pivottable/images/tests.svg)](http://nicolas.kruchten.com/pivottable/tests/) [![license](http://nicolas.kruchten.com/pivottable/images/license.svg)](https://github.com/nicolaskruchten/pivottable/blob/master/LICENSE.md)


# PivotTable.js

PivotTable.js is a Javascript Pivot Table library with drag'n'drop functionality built on top of jQuery/jQueryUI and originally written in CoffeeScript by [Nicolas Kruchten](http://nicolas.kruchten.com) at [Datacratic](http://datacratic.com). 

It is available under an MIT license from [CDNJS](https://cdnjs.com/libraries/pivottable) and [NPM](https://www.npmjs.com/package/pivottable) and [Bower](http://bower.io/) under the name `pivottable`.

PivotTable.js can be used with [Python/Jupyter](https://pypi.python.org/pypi/pivottablejs) and [R/RStudio](https://github.com/smartinsightsfromdata/rpivotTable) and you can [try it right now](http://nicolas.kruchten.com/pivottable/examples/local.html) in your browser on a CSV file.

## What does it do?

PivotTable.js' basic function is to enable data exploration and analysis by turning a data set into a summary table and then optionally adding a true 2-d drag'n'drop UI to allow a user to manipulate this summary table, turning it into a pivot table, very similar to the one found in older versions of Microsoft Excel with a bunch of extra developer-oriented features and some visualization effects. With [optional add-ons](https://github.com/nicolaskruchten/pivottable/wiki/Optional-Extra-Renderers), the summary table can be rendered as various kinds of charts, turning the pivot table into a pivot chart.

# PivotTable (pivot.js) with bootstrap styling

This is based on [Nicholas' pivottable.js] (https://github.com/nicolaskruchten/pivottable) but uses bootstrap styling. It uses variables on the html page to pass on the values to pivot.js
Basically, we have just updated three files:
* pivot.js: to accomodate new bootstrap variables and new styling
* pivot.css: new styling which is streamlined with bootstrap and other new stlyling attributes
* mps_csv.html: the only example I've updated to show the new changes

Our changes are live on mps_csv.html file which you can see by clicking on "pivotUI() with C3 chart renderers" example from the homepage. We've not tested with the other renderers so far but I am hopeful it will work with other renderers as well. For some it might require a little update.

## Screenshots

### Barchart
![image](https://cloud.githubusercontent.com/assets/6144048/17784836/09db8b8c-654c-11e6-8da0-8e755bba63e3.PNG)

### Heatmap
![image](https://cloud.githubusercontent.com/assets/6144048/17784838/09ee03a2-654c-11e6-90d0-e21ee7fd7eb9.PNG)

### Col heatmap
![image](https://cloud.githubusercontent.com/assets/6144048/17784837/09e3cb26-654c-11e6-895e-0d2a5f47bad9.PNG)

### Row Heatmap
![image](https://cloud.githubusercontent.com/assets/6144048/17784839/09eeb158-654c-11e6-8b93-5690214b1231.PNG)

## Copyright & Licence (MIT License)

PivotTable.js is © 2012-2016 Nicolas Kruchten, Datacratic, other contributors

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
