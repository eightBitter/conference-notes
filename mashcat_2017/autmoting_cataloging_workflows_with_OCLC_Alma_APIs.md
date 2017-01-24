Automating Cataloging Workflows with OCLC and Alma APIs
========================

Presenters
----------

- Erin Grant
- Alex Cooper

Notes
-----

- complex library organization brought about complex challenges
- Metadata service and Core services (IT)
- "API fever" for apps
- put in failsafes for double-checking batch holding deletes before actually deleting
- two processes
	- delete holdings records with no bib record
	- delete holdings recrod from withdrawn records
- PromptCat App
	- service where you get records from vendors and *something*

QA
--

- was there good documentation for the SRU APIs?
	- documentation is very good
	- Ex Libris has built an API console that assists with building the code
	- OCLC script was a little harder, because it is encrypted
- did you need support from OCLC or Ex Libris?
	- not really
- what else can you do with the APIs?
	- the analytics API is pretty powerful
