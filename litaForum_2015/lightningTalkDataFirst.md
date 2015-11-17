Lightning talk: Data First!
=============

Jacob Shelby, Iowa State University

- hare-brained idea that manifested the day of the lightning talks
- "What would the digital world look life if we started with the data?"

Current state
-------------

- in building a tool, we choose a metadata standard/schema to use, then **very rarely** expose datasets at the end
- or, choose a tool and confine our metadata to fit its structure. when moving to another tool, we have to migrate our data to conform to the new tool's structure

New paradigm
------------

- *(more appropriate for Linked Data, when you can tap into endpoints)*
- design metadata model, expose datasets via an endpoint like an API or SPARQL, then build tools from the endpoint
- institutions would expose all of their data from endpoints (ex. Library of Congress subject and name authorities, Getty thesaurus and geographic names)
  - people and institutions could connect to all of the data

Benefits
--------

- leverage reuse of data
  - publish once, reuse
  - RDF helps facilitate reuse by linking data together
  - no more duplication
- modular data = limitless types of tools
  - existing examples include Digital Public Library of America's API model
- not bound to a single standard/schema

Challenges
----------

- wild west of metadata (round two)
  - since RDF is not bound to a single schema, Linked Data can become very wild
  - will need some sort of standardization
    - doesn't mean you have to build a new schema. just need to have consensus on the properties and classes to use
      - maybe in the future there will be a mechanism in place to perform "live" mappings instead of relying on tools such as XSLT to map between schemas
- librarians will need more coding proficiencies
  - this seems like the going trend anyway
- will need best practices for publishing Linked Data and API query parameters
