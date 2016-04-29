# solrgraph
Simple tool allowing to visualize Solr graph query (http://solr.pl/en/2016/04/18/solr-6-0-and-graph-traversal-support/)

## Running
* Download graph.html
* Put graph.html to $SOLR_HOME/server/solr-webapp/webapp
* Open http://localhost:8983/solr/graph.html in your favorite browser

## Limitations
* Not tested on larger data sets
* Not pretty
* Not resistant to CORS

## Plans
* Test on larger data sets
* Style it better
* Make it resistant to CORS
* Support for filtering in graph query
* Support for all parameters allowed in graph query

## Changes
Changes introduced with each version.

### 0.3
* Released 29.04.2016
* Support for q parameter
* Styling changes

### 0.2
* Released 25.04.2016
* Tooltip with document fields on mouse over graph node
* Data loaded page by page

### 0.1
* Released 24.04.2016
* Initial version
* Allows providing basic information and visualize graph
* No paging
* No filtering
* No control over q parameter
