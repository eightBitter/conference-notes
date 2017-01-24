Reconciling Legacy Archival Metadata
===========================

Presenters
----------

- Greer Martin

Notes
-----

- efforts to migrate archival data from old database to an instance of ArchivesSpace
- goal to migrate 5k records from old database to ArchivesSpace
- records lacked authority control
	- also two different name databases
- use OpenRefine to reconcile authorities against LC linked data service
- adding an identifier to local names for future possible linked data projects
- example reconcile code: https://lc-reconcile.herokuapp.com
	- https://github.com/cmh2166/lc-reconcile
- issue: takes a good amount of time to do manual QC of the reconciled records
- used a second service for the rest of the reconciliation bc the first process was daunting
	- reconcile-CSV
		- another OpenRefine extension
		- was much faster than the other reconciliation service
- tried reconcile-CSV for reconciling subjects
- evaluating LC matches + creating local names took the most time
- recommends reconcile-CSV as a supplement

QA
--

- would you be willing to share the volunteer manual?
	- yep
- how did reconcile-CSV help supplement?
	- the first reconcile ran against LC and gave back a subset that could be more easily reconciled against the rest of the list using reconcile-CSV
- now that the project is done, how are you actively updating?
	- periodically checking?
- *currently an IMLS project looking at how we can batch create NACO/SACO records*
- how did you get the subject names to work?
	- a lot of manual intervention before the reconciliation
- did you consider FAST?
	- yes
	- possibly include FAST in future projects
	- interest in enhancing the subject terms in the future
