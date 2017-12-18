# STORYLENS

The multistream corpora (StoryLens) created for Recognyze eval in InVID project.

## A MULTISTREAM CORPORA

A multistream corpora contains content from different types of streams. 

The current corpora contains annotations based on the following stream types: 

* news - 100 documents
* twitter - 200 documents
* youtube - 100 documents

We might consider adding more documents in time.

## DOCUMENTS
The YouTube, Twitter and newsmedia documents are not provided with this corpus due to copyright reasons.

The original documents can be retrieved by crawling their URLs. In order to provide third parties with the possibility to do this we provide a list of Document Ids in the following folder: [List](https://github.com/modultechnology/storylens/tree/master/lists). Here are the links to the individual lists:
* [Tweets](https://github.com/modultechnology/storylens/blob/master/lists/tweets.csv)
* [YouTubes](https://github.com/modultechnology/storylens/blob/master/lists/youtubes.csv)
* [News](https://github.com/modultechnology/storylens/blob/master/lists/news.csv)

The output for the Twitter partition of the corpora only contains the annotations due to copyright restrictions, but the actual texts of the tweets can be downloaded by ids using free scripts\footnote{Tweet Downloader by ID example: https://gist.github.com/giacbrd/b996cfe2f1d24752f23bd119fdd678f2}.

## ONTOLOGY

The focus is on location entities, therefore all types of conflicts between locations
and other types of entities are included.

The annotations taken into account when building the gold standard files are the following:
* Natural Location (LOC) - e.g., Danube River, Alps
* Geo-Political Entity (GPE) - e.g., Vienna, Austria
* Facility (FAC) - e.g., Brooklyn Bridge, Interstate 66
* Person (PER) - e.g., Prince Charles, Donald Trump
* Organization (ORG) - e.g., Google, Apple
* Product (PROD) - e.g., IPhone, Samsung Galaxy 8
* Work (WORK) - e.g., Mona Lisa, Star Trek
* Event (EVENT) - e.g., 9/11, Grenfell Tower fire
* misc (MISC) - any other type of entity

The ontology can be found here: [Recognyze Ontology](https://github.com/modultechnology/storylens/blob/master/ontology/recognyze).

## ANNOTATION GUIDELINE

The Annotation Guideline is based on TAC and ACE guidelines.

It can be found in the following folder: [Guideline](https://github.com/modultechnology/storylens/tree/master/guideline).

## GOLD

The [Gold](https://github.com/modultechnology/storylens/tree/master/gold) folder contains the judged results. 

The links provided are based on the current LIVE DBpedia (September - December 2017) version that would correspond to DBpedia 2017-10 or 2018-04, therefore link changes can occur.

In case you find one of the following error types please feel free to contact us in order to update it:
* New entities that were not annotated
* Different possibilities to annotate various entities
* New links (where no entitiy was found before or where NIL entities currently exist)

## LENSES
The [Lenses](https://github.com/modultechnology/storylens/tree/master/lenses) folder contains some exmple lenses.

We currently provide:
* Long - longest match for any entity
* Embedded - includes embedded entities
* (DBpediaLens - lens related to a certain DBpedia version (e.g., 2016-10 or 2016-04) - currently in preparation)

For future versions of the corpora we will also include:
* events - arguably only named events (EVENT) such as Grenfell Tower Disaster
* stories - the narratives focused around big events

## OTHER FORMATS

If there is a need to use this corpora in other formats than the ones provided by us, please contact us.

## NOTES
Official version is published on GitHub without the original documents due to copyright reasons.

If you plan to use this corpora in an evaluation suite please contact us.

If you discover various errors in this dataset (e.g., missing annotation, wrong types, etc,) feel free to contact us and we will update it.

## COPYRIGHT
Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)
