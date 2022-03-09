# Introduction to SnowFlake 






 Snowflake is a Data Cloud is powered by an advanced data platform provided as Software-as-a-Service (SaaS). Snowflake enables data storage, processing, and analytic solutions that are faster, easier to use, and far more flexible than traditional offerings.

Snowflake combines a completely new SQL query engine with an innovative architecture natively designed for the cloud. To the user, Snowflake provides all of the functionality of an enterprise analytic database, along with many additional special features and unique capabilities.


**In this Topic:**

### 1. Data Platform as a Cloud Service 
### 2. Snowflake Architecture

 * Database Storage

* Query Processing

* Cloud Services

### 3. Connecting to Snowflake

## Data Platform as a Cloud Service

Snowflake is a true SaaS offering. 
  * There is no hardware (virtual or physical) to select, install, configure, or manage.

* There is virtually no software to install, configure, or manage.

* Ongoing maintenance, management, upgrades, and tuning are handled by Snowflake.

## Snowflake Architecture 

Snowflake’s unique architecture consists of three key layers:
  * Database Storage

* Query Processing

* Cloud Services

![Snowflake Architecture view](https://docs.snowflake.com/en/_images/architecture-overview.png)

## Database Storage

When data is loaded into Snowflake, Snowflake reorganizes that data into its internal optimized, compressed, columnar format. Snowflake stores this optimized data in cloud storage.

 The data objects stored by Snowflake are not directly visible not accessible by customers; they are only accessible through SQL query operations run using Snowflake.

## Query Processing

Query execution is performed in the processing layer. Snowflake processes queries using “virtual warehouses”.

Each virtual warehouse is an independent compute cluster that does not share compute resources with other virtual warehouses. As a result, each virtual warehouse has no impact on the performance of other virtual warehouses.

## Cloud Services

The cloud services layer is a collection of services that coordinate activities across Snowflake. These services tie together all of the different components of Snowflake in order to process user requests, from login to query dispatch. 

Services managed in this layer include:

   * Authentication

   * Infrastructure management

   * Metadata management

* Query parsing and optimization

*  Access control
## Connecting to Snowflake

Snowflake supports multiple ways of connecting to the service:

* A web-based user interface from which all aspects of managing and using Snowflake can be accessed.

* Command line clients (e.g. SnowSQL) which can also access all aspects of managing and using Snowflake.

For more information, see [Logging into snowflake](https://docs.snowflake.com/en/user-guide/connecting.html)

## Loading Data into Snowflake

Below are the topics how to load(import) data intto snowflake database

* Key concepts related to data loading, as well as best practices.

  * [Data Loading](https://docs.snowflake.com/en/user-guide/data-load-overview.html)



  * [Summary of Data Loading Features](https://docs.snowflake.com/en/user-guide/intro-summary-loading.html)

  * [Data Loading Considerations](https://docs.snowflake.com/en/user-guide/data-load-considerations.html)

* supported data file formats and data compression.

  * [Preparing to Load Data](https://docs.snowflake.com/en/user-guide/data-load-bulk.html)

 * Detailed instructions for loading data in bulk using the COPY command.

   * [Bulk Loading Using COPY](https://docs.snowflake.com/en/user-guide/data-load-snowpipe.html)

 * Detailed instructions for loading data continuously using Snowpipe.

   * [Loading Continuously Using Snowpipe](https://docs.snowflake.com/en/user-guide/data-load-web-ui.html)

 * Basic instructions for loading limited amounts of data using the web interface.

   * [Loading Using the Web Interface (Limited)](https://docs.snowflake.com/en/user-guide/data-load-web-ui.html)

* How to execute queries on staged data and transforming data while loading it into tables.

  * [Querying Data in Staged Files](https://docs.snowflake.com/en/user-guide/querying-stage.html)

  * [Querying Metadata for Staged Files](https://docs.snowflake.com/en/user-guide/querying-metadata.html)

  * [Transforming Data During a Load](https://docs.snowflake.com/en/user-guide/data-load-transform.html)

### References
  * 1.Google Search
  * 2.Websiteh: https://docs.snowflake.com/en/
  * 3.Youtube : https://www.youtube.com/watch?v=xojAXXRo_S0
 















