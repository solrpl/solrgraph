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
* Support for any query user would like to run
* Support for filtering in graph query
* Support for all parameters allowed in graph query