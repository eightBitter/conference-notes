Automating controlled subject access from IR keyword strings
=======================

Presenters
----------

- Matthew Miguez

Notes
-----

- moved from BePress to Islandora
- talked about the LC LD service API
- reconciled local authorities against LC LD service API using (it looks like) Python
- currently storing the linked data in the backend that can be used for future projects 
- addURI.py: http://big.ly.2jNoegD
	- build on LXML and pymods

QA
--

- interest in doing this with things other than keywords?
	- yes, want to extend it to work with teh NAF, also breaking apart complex subject headings
- adding a caveat to records about how they've been processed?
	- not at the moment
	- currently trust the system to work
- what happens when there's no match?
	- keep text string
- do any manual matching for non-matches?
	- not enough time
