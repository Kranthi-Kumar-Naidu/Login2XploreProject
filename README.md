# Login2XploreProject
**Web Form using JsonPowerDB**
The project is based on a web form which accepts data from user and uploads the data into database on submission. The form has been implemented using bootstrap, jquery and javascript. The database used is jsonPowerDB which is a Real-time, High Performance, Lightweight and Simple to Use, Rest API based Multi-mode DBMS. JsonPowerDB has ready to use API for Json document DB, RDBMS, Key-value DB, GeoSpatial DB and Time Series DB functionality. JPDB supports and advocates for true serverless and pluggable API development.

**Benefits of using JsonPowerDB**
* Simplest way to retrieve data in a JSON format.
* Schema-free, Simple to use, Nimble and In-Memory database.
* It is built on top of one of the fastest and real-time data indexing engine - PowerIndeX.
* It is low level (raw) form of data and is also human readable.
* It helps developers in faster coding, in-turn reduces development cost.

**Release History:**
0.3.2 / 2020-10-08
==================

* Added : Added Plugin API Framework in JsonPowerDB.
* Added : Added a new class APISyntaxValidator to check syntax of request json.
* Added : Added a new APIs for column operation and implement it using pluggable framework:
             Copy Column - It will copy column in database.
             Rename Column - It will rename column in database.
             RemoveColumn - It will remove column in database.
             Change Column type - It will change type of column in database.
* Improved : In Geospatial distance API to pick create time column (sorted in ascending) as time range 
             (by default it should pick the record creation time from the JPDB system file internal 
             recorded time) defined in request fromTime to toTime.
* Fixed : Fixed important bugs.  


**Sample snapshots:**

Format: ![JsonPowerDB Interface](https://github.com/BeAgarwal/JsonPowerDB/blob/master/Assets/Screenshots/Server.PNG)
