## List of the transportation related data standards and formats
---- ---- ---- ---- ----

| Dataset standard  | Description  |
| ------------- | ------------- |
| GBFS (General Bikeshare Feed Specification) | The GBFS is an open data standard for shared mobility. <br /> https://gbfs.mobilitydata.org/ <br /> https://github.com/NABSA/gbfs |
| GTFS (The General Transit Feed Specification) | GTFS static or static transit to differentiate it from the GTFS realtime extension, defines a common format for public transportation schedules and associated geographic information. GTFS "feeds" let public transit agencies publish their transit data and developers write applications that consume that data in an interoperable way. <br/> https://developers.google.com/transit/gtfs |
| GTFS Realtime | Providing users transit data updates in real time greatly enhances their experience of your transit services. Providing up-to-date information about current arrival and departure times allows users to smoothly plan their trips. As a result, in case of an unfortunate delay, a rider would be relieved to know that they can stay home a little bit longer. <br/> https://developers.google.com/transit/gtfs-realtime |
|DATEX II| Datex II or Datex2 is a data exchange standard for exchanging traffic information between traffic management centres, traffic service providers, traffic operators and media partners. <br> https://datex2.eu/|
|TN-ITS| TN-ITS is concerned with information exchange on changes in static road attributes. Road safety and efficiency require highly updated digital maps for ITS, but map providers struggle to keep these elements current. The solution is to retrieve the information on changes from the road authorities. As regulators of these changes, e.g., speed limits, they are the most immediate and reliable source for such information.  <br> https://tn-its.eu/about-us/|
|APDS (ALLIANCE FOR PARKING DATA STANDARDS)|The Alliance for Parking Data Standards (APDS), formed in 2018 by the International Parking and Mobility Institute (IPMI), the British Parking Association (BPA), and the European Parking Association (EPA), is a not-for-profit organization with the mission to develop, promote, manage, and maintain a uniform global standard that will allow organizations to share parking data across platforms worldwide. <br> https://www.europeanparking.eu/en/activities/parking-alliance/|
|NPTG (National Public Transport Gazetteer)|NPTG a database of localities (cities, towns, villages and other settlements) in Great Britain. It provides a common frame of reference for the National Public Access Nodes (NaPTAN) schema.<br> https://www.data.gov.uk/dataset/3b1766bf-04a3-44f5-bea9-5c74cf002e1d/national-public-transport-gazetteer-nptg|
| MDS (Mobility Data Specification) | https://www.openmobilityfoundation.org/about-mds/ <br /> https://github.com/openmobilityfoundation/mobility-data-specification |
| TransXChange | UK nationwide standard for exchanging bus schedules and related data. <br/> https://www.gov.uk/government/collections/transxchange |
| Siri (Standard Interface for Real-time Information) |SIRI is an XML protocol that allows the exchange of real time information about public transport services and vehicles. <br/> https://www.transmodel-cen.eu/siri-standard/ <br/> www.normes-donnees-tc.org/wp-content/uploads/2021/10/BNTRA-CN03-GT7_NF-Profil-SIRI-FR_v1.2_20210308.pdf |
|Wikidata|Wikidata is an open-licensed collaborative structured database that supports Wikipedia and other projects of the Wikimedia Foundation. <br/> http://junglebus.io/MobilityData/benchmarks/Transport%20data%20models%20comparative%20review.html#Wikidata|
| DJP/OJP (Open API for distributed journey planning) | OJP initiative was born to answer the esigence to exchange accurate and timely information about public transport (PT) servicesand  to implement systems able to provide Multi-modal information for longer-distance journeys. <br/> https://www.transmodel-cen.eu/ojp-standard/ |
| NeTEx (Network Timetable Exchange) | NeTEx is a CEN Technical Standard for exchanging Public Transport schedules and related data. <br/> https://netex-cen.eu/ <br> https://netex-cen.eu/?faq=how-does-netex-compare-with-gtfs |
| OpRa (Operating Raw Data and statistics exchange) | OpRa is an CEN initiative with main focus on the identification of Public Transport raw data to be exchanged, gathered and stored in order to support Study and Control of Pubic Transpoprt Service. <br/> https://www.opra-cen.eu/overview/ |
| HAFAS | The HaCon timetable information system (HAFAS) is software for timetable information from the company HaCon (Hannover Consulting). HaCon has been a 100 percent subsidiary of Siemens AG since 2017. Deutsche Bahn AG, the Austrian Federal Railways and the Swiss Federal Railways as well as numerous other European transport companies, such as the public transport company TPG, use HAFAS on a broad basis. In particular, the online timetable information for customers is realized with it. <br/>  https://de.wikipedia.org/wiki/HAFAS |
| HAFAS Raw Data Format (HRDF)| The timetable data of a transport provider must be available in the Hafas raw data format in order to obtain advantange of the Hafas timetable information system. This format is the starting point for the Transform data treatment which generates a specialised binary data format from the raw data. This binary data format is tailored to the needs of the search algorithm and thus enables optimum information to be found in a very short time. <br/> https://transportdatamanagement.ch/content/uploads/2020/04/HRDF.5.20.39-Guidelines-e.pdf |
| TRANSMODEL | Transmodel is the basis for defining exchange standards that enable the sharing and provision of accurate and interoperable public transport information across organisation- and system-boundaries. <br/> https://www.transmodel-cen.eu/transmodel-at-a-glance/ <br /> https://www.transmodel-cen.eu/siri-standard/ |
| DVC (Data Communication on Vehicles* | Standardization of the application rules concerning the WORLDFIP or CAN data bus transmission. Environmental and electrical conditions and limits inside the vehicle. <br/> https://www.transmodel-cen.eu/dcv-standard/ |
|MapInfo|Sometimes called the MapInfo Native format or the MapInfo TAB format, the MapInfo dataset format is a proprietary format developed for use with MapInfo software products. <br> https://www.loc.gov/preservation/digital/formats/fdd/fdd000300.shtml|

---- ---- ---- ---- ----
## Dataset formats
| Entity | Description |
| ------------- | ------------- |
|CSV|Files with .csv (Comma Separated Values) extension represent plain text files that contain records of data with comma separated values.  <br> https://docs.fileformat.com/spreadsheet/csv/|
|HTML|Users can use normal HTML tables and another structured markup as data sources with the Spry HTML dataset. HTML datasets function similarly to XML datasets, with the exception that they can take advantage of the millions of tables that are available. The HTML dataset was a natural expansion of the Spry Framework because we flatten XML into a table structure. <br> https://www.educba.com/dataset-in-html/ |
|QGIS|QGIS uses the OGR library to read and write vector data formats, including ESRI shapefiles, MapInfo and MicroStation file formats, AutoCAD DXF, PostGIS, SpatiaLite, Oracle Spatial and MSSQL Spatial databases, and many more.<br>https://docs.qgis.org/2.8/en/docs/user_manual/working_with_vector/supported_data.html|
| O5m | The .o5m data format was designed to be a compromise between .osm and .pbf format. It has the same structure as .osm format, therefore input and output procedures of existing OSM data processing applications can be adapted to this format with small effort. <br/> https://wiki.openstreetmap.org/wiki/O5m |
|Level0L|Level0L (or l0l in short) is a format compatible with OSM XML. It is used in the Level0 editor. <br> https://wiki.openstreetmap.org/wiki/Level0L|
| JSON | JSON (JavaScript Object Notation) is a lightweight data-interchange format. <br /> https://www.json.org/json-en.html <br />  https://www.w3schools.com/js/js_json_intro.asp|
| GeoJSON | GeoJSON is a format for encoding a variety of geographic data structures. <br/> https://geojson.org/|
| XML(Extensible Markup Language) |  XML is a markup language and file format for storing, transmitting, and reconstructing arbitrary data. <br /> https://www.xml.com/ |
| OSM XML | The major tools in the OSM universe use an XML format following a XML schema definition that was first used by the API only. <br/> https://wiki.openstreetmap.org/wiki/OSM_XML |
|OSM JSON|OSM API JSON format is based on the Overpass API JSON format with only minor differences in the header fields. <br> https://wiki.openstreetmap.org/wiki/OSM_JSON <br> http://overpass-api.de/output_formats.html|
| PBF ("Protocolbuffer Binary Format")  | A lot of software used in the OSM project already supports PBF in addition to the original XML format, plus there are several tools to convert from PBF to OSM XML and vice versa. <br/> https://wiki.openstreetmap.org/wiki/PBF_Format |
|XYZ Data|XYZ data are point clouds representing measurements in arbitrary sets of points in the xy plane. <br> http://gwyddion.net/documentation/user-guide-en/xyz-data.html|
|KML|KML is a file format used to display geographic data in an Earth browser such as Google Earth. <br> https://developers.google.com/kml/documentation/kml_tut |
|Shapefile|A shapefile is a simple, nontopological format for storing the geometric location and attribute information of geographic features. Geographic features in a shapefile can be represented by points, lines, or polygons (areas).  <br> https://desktop.arcgis.com/en/arcmap/10.3/manage-data/shapefiles/what-is-a-shapefile.htm|
|STEP|STEP files are commonly used in computer-aided design (CAD) and 3D printing to contain three-dimensional model data for a wide variety of design tasks. <br>https://docs.fileformat.com/3d/step/|
| NetCDF|NetCDF (Network Common Data Form) is a set of software libraries and self-describing, machine-independent data formats that support the creation, access, and sharing of array-oriented scientific data. <br> https://en.wikipedia.org/wiki/NetCDF|
|MapInfo TAB format|https://www.loc.gov/preservation/digital/formats/fdd/fdd000300.shtml|
|.ID|Stores information linking graphic data to the database information. This contains a 4-byte integer index into the MAP file for each feature. <br>https://www.loc.gov/preservation/digital/formats/fdd/fdd000300.shtml |
|.MAP|Map objects are stored in binary format and represented in a .MAP file. <br> https://www.loc.gov/preservation/digital/formats/fdd/fdd000300.shtml|
|Resource Description Framework (RDF)|RDF datasets are used to organize collections of RDF graphs, and comprise a default graph and zero or more named graphs. <br> https://www.w3.org/TR/rdf11-concepts/|
|RSS (RDF Site Summary or Really Simple Syndication)|RSS formats are specified using a generic XML file. <br> https://en.wikipedia.org/wiki/RSS |

## Data Models
|Data Model|Link|
|--|--|
|INSPIRE UML|TEXT <br> https://inspire.ec.europa.eu/Data-Models/Data-Specifications/2892|
|NAME|TEXT|

## APIs
|API|Link|
|--|--|
|Navitia|https://navitia.io/|
|ArcGIS REST APIs|The ArcGIS REST API allows you to administer ArcGIS Server programmatically. This means that you can completely manage your server using any framework that can make HTTP requests.  <br> https://developers.arcgis.com/rest/enterprise-administration/server/overview.htm|
|Nextbus API|https://www.data.gov.uk/dataset/15be9dba-392c-4375-a931-425e35b956f7/nextbuses-api <br> https://gist.github.com/grantland/7cf4097dd9cdf0dfed14|
|Mobility Lab|https://mobilitylab.org/transit-api-database/#apis|


## Database
| Source | Link |
| ------------- | ------------- |
| New York | https://nycopendata.socrata.com/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9? |
|Franch government (Transportation) |https://transport.data.gouv.fr/|
|OpenStreetMap|https://welcome.openstreetmap.org/what-is-openstreetmap/|
|The home of the U.S. Government’s open data|https://data.gov/|
|California Open Data portal|https://data.ca.gov/dataset|
|Catalog Data Gov|https://catalog.data.gov/dataset|
|Data Gov UK|https://www.data.gov.uk/search?filters%5Btopic%5D=Transport|
|NaPTAN Database|https://www.gov.uk/government/publications/national-public-transport-access-node-schema/html-version-of-schema|
|NCSD (National Coach Services)|https://www.data.gov.uk/dataset/3a3b32f3-d727-4623-aa17-daa2f39aaf92/national-coach-services-ncsd|
|Traveline National Dataset|https://www.data.gov.uk/dataset/0447f8d9-8f1b-4a68-bbc8-246981d02256/traveline-national-dataset|


 

