Data Remediation: A View from the Trenches
==========================================

Heather Wilson, not identified

Christina Harlow, University of Tennessee Knoxville

Introduction
------------

materials: <https://goo.gl/MFZP1t>
- google apps script editor
- marcEdit
- openRefine
- scripting (Python, Catmandu)
- ERM tools tutorial

Google apps script editor
-------------------------

- works great with Google Drive stuff
- can easily pull in stuff from Google Mail
- extensive documentation
- something about SUSHI endpoint
	- counter reports
	- SUSHI calls for pulling in electronic journal data

MARCEdit
--------

- reconcialation
- Linked Data tools
	- will reconciliate 1xx, 6xx, etc and pull in URI from id.loc.gov and put it in a subfield 0

OpenRefine
----------

- java and jetty
- LOD Refine
- reconciliation
	- reconciliation service API
- [cmh2166](http://github.com/cmh2166)
	- Christina's GitHub account

Scripting Python + PyMARC, Catmandu (Perl)
-------------------

- MARCEdit can't handle very large datasets, so sometimes you need to work scripting languages directly
