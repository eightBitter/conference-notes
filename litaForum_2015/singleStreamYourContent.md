Single-Stream Your Content: Tools For Consolidating Multiple Repositories into Islandora
============================

Spencer Lamm, Drexel

Chris Clement, Drexel

Introduction
------------

- in 2013 had separate silos
- multiple repositories
	- DSpace
	- Library Website
	- local/custom development solution
- multiple locations
	- website
	- disk storage
	- Fedora Commons
- impacts
	- silos for patron discovery
	- disjointed administration of content for staff
	- multiple technologies
- where we wanted to be
	- use Islandora as the central repository

Issues
------

- legacy content
	- dspace hierarchy, metadata
- unsupported content types
	- finding aids
	- exhibitions
- feature envy

Data Migration
--------------

- custom hierarchical importer
	- allows multiple content types
- prep scripts for DSpace and finding aids

Feature Enhancements
--------------------

- customized collection display
- cust record display
- fielded relevance ranking with boots
- finding aid ingestion, display, and search
- default batch importers
	- scan batch
		- single content type
		- single relation to parent object
	- book batch
		- ingest books
		- batches required to be in a  predefined structure

- hierarchical importer
	- each object is a directory
	- special files
		- assign specific IDs
		- assign content types
		- assign relationship to other files
- EAD exports of finding aids from Arch Toolkit provided by the Archives
- customized record display
	- picked pieces of metadata from various streams, gave them labels

- finding aid support
	- new content model
	- ingest, display, search on EAD finding aids
	- fully integrated finding aids with digital objects
		- *(cool!)*
