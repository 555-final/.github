####Authors:
Henry Chen (henchen)
Aydan Gooneratne (aydang)
Evan Si (anthias)
Constance Wang (conswang)

####Features
Each of us was responsible for a different part of this project.
Henry worked on the UI frontend; Aydan worked on a distributed crawler that would index pages; Evan worked on an indexer that would parse the pages and create tf-idf scores; Constance worked on the PageRank side.

No extra credit was done for this project.

####Source Files
Each project has their own list of source files:
Crawler: Crawler.java, DOMParserBolt.java, FetcherBolt.java, LinkEnqueuerBolt.java, URLSpout.java, UploaderBolt.java, AWSController.java, AWSFactory.java, UrlItem.java, HttpIOHandler.java, HttpResponse.java, StorageFactory.java, StorageImpl.java, StorageInterface.java, RobotsPolicy.java, URLInfo.java, & the Stormlite library.
Web Interface: ResultsPage.jsx, SearchPage.jsx, App.jsx, constants.js, index.js, reportWebVitals.js, App.css, index.css
Web Server: Database.java, Document.java, Query.java, WebServer.java
Indexer: Indexer.java, HTMLFileInput.java, DocMapper.java, DocReducer.java, TFIDFMapper.java, TFIDFReducer.java
PageRank: SparkSetup.java, PageRank.java

####To Run
Indexer, Crawler, PageRank, WebServer - the files can be installed as a Java Maven project and run accordingly
Web Interface - run like any othe react project (e.g., npm run build)