Using Big Data Techniques for Metadata Remediation
=============================

Presenters
----------

- Roy Tennant

Notes
-----

- "making the data work harder"
- MapReduce
	- look this up on Wikipedia for definition
	- they use Hadoop
- Apache Hadoop, Spark
- Spark = real-time processing
- Hadoop is java native
	- however, can use any language you want
- Hadoop Distributed File System (HDFS) takes care of disctributing data across clusters
- map processing
	- find all records with a certain field, a certain string, etc
- *examples of mappers and reducers used at OCLC*
- putting this into the hands of non-programmers
- production version of WorldCat is in Hadoop
- TRecX UI (Data Manager) is a layer on top that gives more power to non-programers
	- "Scope": fields you want to process
	- "Filter": subfield or text string you want to work on
	- "Action": delete, replace, rename, etc
- Data Manager is in WorldShare
	- has a library of all scripts used in the OCLC community so you can reuse
	- has preview option to check results before processing
- *demonstration of WorldShare Data Manager*

QA
--

- how does this relate to the MARC Usage service
	- nothing to do with TRecX
	- Roy does manual tweaks to a script
- does the validation to into account *something*
	- not sure
- would this scale to linked data?
	- conceivably
	- don't think the data presents a problem
	- software is data agnostic
	- you (the processor) would need to know the data you're trying to process
	- requires flat files. wouldn't work on a SPARQL endpoint
