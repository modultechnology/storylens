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

## DOCUMENTS
The YouTube, Twitter and newsmedia documents are not provided with this corpus due to copyright reasons.

The original documents can be retrieved by crawling their URLs. In order to provide third parties with the possibility to do this we provide a list of Document Ids in the following folder: [List](https://github.com/modultechnology/storylens/tree/master/lists). Here are the links to the individual lists:
* [Tweets](https://github.com/modultechnology/storylens/blob/master/lists/tweets.csv)
* [YouTubes](https://github.com/modultechnology/storylens/blob/master/lists/youtubes.csv)
* [News](https://github.com/modultechnology/storylens/blob/master/lists/news.csv)

The output for the Twitter partition of the corpora only contains the annotations due to copyright restrictions, but the actual texts of the tweets can be downloaded by ids using free scripts\footnote{Tweet Downloader by ID example: https://gist.github.com/giacbrd/b996cfe2f1d24752f23bd119fdd678f2}.


Official version will be published on GitHub without the original documents due to copyright reasons.
