# Datacore concepts

## Data formats 
  Structured
  Semi structure
  Unstructured
## Options for data storage in files
Delimited text files
			CSV (comma separated value)
			TSV (Tab separated value)
			Space delimited
			Fixed-width 
JavaScript Object Notation (JSON)
			JSON is a ubiquitous format in which a hierarchical document schema is used to define data entities (objects) that have multiple attributes. 
   			Each attribute might be an object (or a collection of objects); making JSON a flexible format that's good for both structured and semi-structured data.
Extensive Markup Language (XML)
Binary Large Object (BLOB)
Optimized file formats
			Avro
   			ORC
      			Parquet
  
## Options for data storage in databases
Relational database
Non relational database
	Key-valua database
 	Document database
  	Column family database
   	Graph database

 ## characteristics of transactional data processing solutions
	Atomicity
 	Consistency
  	Isolation
   	Durability

## Describe characteristics of analytical data processing solutions
	 1. Data files may be stored in a central data lake for analysis.
	 2. An extract, transform, and load (ETL) process copies data from files and OLTP databases into a data warehouse that is optimized for read activity. 
	 3. Data in the data warehouse may be aggregated and loaded into an online analytical processing (OLAP) model, or _cube_. 
	 4. The data in the data lake, data warehouse, and analytical model can be queried to produce reports, visualizations, and dashboards.
  
