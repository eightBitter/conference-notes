Searching for sound: implementing a discovery layer for music
============================

Presenters
----------

- Kyle Shockey
- Yamil Suarez
- Mary Jinglewski
- Ellie Collier

Notes
-----

- project from Berklee
- two schools, two libraries, two ILSs, wanted one discovery layer
- metadata aggregation from two sets of MARC
	- works better for text than sound
- MLA published Music Discovery Requirements: http://www.musiclibraryassoc.org/?page=mdr
- lots of works, lots of genres, lots of types, etc
- sites of granularity loss
	- systems not set up well for authority linking
- EDS (Ebsco Data Service)
- mobile view cannot be customized (easily breakable)
- issues
	- two of everything: authentication systems, networks and IP addresses
- would like to set up ERM platform like CORAL
- Authorities in Evergreen ILS
- on the backend there are authority control sets
- able to have custom authority records
- discussion about song title limiter
	- full text, audio, music scores, video
	- used the IL MARC tag for storing song titles

QA
--

- can you talk about what subfield 0 does?
	- used as a unique identifier
- proliferation of subject thesauri. how adaptable is Evergreen to the thesauri?
	- haven't run into a limit yet
- are you able to match to a specific authority file based on subfield 2?
	- yes
