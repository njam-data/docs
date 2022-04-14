# Tools & resources

## Reusable tools for data projects, each with their own documentation:
- Commonly needed javascript functions for working with data https://github.com/njam-data/tools
- Calculate a diversity index using the USA Today composite index https://github.com/njam-data/diversity-index
- Reusable UI components for data projects (starting small with a d3 graph) https://github.com/njam-data/components
- A starterkit repo for making aws lambda functions https://github.com/njam-data/njam-lambda-node
- A slack monitoring for scrapers and other processes https://github.com/njam-data/slack-data-pipeline-monitor
- Command-line tools for common development tasks (starting with converting xlsx files to csv) https://github.com/njam-data/njam

## Geospatial data
- Transform between geospatial projections using node.js https://github.com/proj4js/proj4js
- Find spatial references for projecting data here https://spatialreference.org
- Simplify geojson geometries https://www.npmjs.com/package/simplify-geojson

## Data cleaning & analysis
- daff https://github.com/paulfitz/daff
- csvkit https://csvkit.readthedocs.io/en/latest/
- sqlite-utils https://github.com/simonw/sqlite-utils

## PDF Parsing

We always need to parse a lot of PDFs.

It would be cool if there were a processing pipeline set up with lambda / ecs / stepfunctions / google cloud where it attempts multiple types of parsing.

## Possible parsers
- amazon pdf parser https://aws.amazon.com/textract/
- https://github.com/adrienjoly/npm-pdfreader
- https://cloud.google.com/vision/docs/pdf
- https://tabula.technology
- https://pdfbox.apache.org (a dependency of tabula)

## Guides, tutorials, retrospectives, etc.

### Accessibility
- Methodology for accessible visualizations https://chartability.fizz.studio/
  - Examples based on Chartability https://observablehq.com/@frankelavsky/chartability

### Common mistakes
- Retrospective from _The Economist_ on improving data visualizations https://medium.economist.com/mistakes-weve-drawn-a-few-8cdd8a42d368

### Tabula guides
- using tabula cli https://github.com/tabulapdf/tabula-java/wiki/Using-the-command-line-tabula-extractor-tool#grab-coordinates-of-the-table-you-want
