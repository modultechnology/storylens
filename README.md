# storylens

The multistream corpora (StoryLens) created for Recognyze eval in InVID project.

It contains 3 types of streams: 

* news - 100 documents
* twitter - 200 documents
* youtube - 100 documents

We might consider adding more documents in time.

The focus is on location entities, therefore all types of conflicts between locations
and other types of entities are included.

The annotations taken into account when building the gold standard files are the following:
* location (GPE, LOC, FAC) entities
* person (PER) and organization (ORG) entities
* products (PROD) and services 
* misc (MISC) - any other type of entity

For some versions of the corpora (lenses) we also include:
* events - arguably only named events (EVENT) such as Grenfell Tower Disaster
* stories - the narratives focused around big events

Current lenses:
* entities
* links
* events and stories


Official version will be published on GitHub without the original documents due to copyright reasons.
