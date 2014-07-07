Discovering the Semantic Type of Events using Social Media
==========================================================

Data used in the paper with title 'Discovering the Semantic Type of Events using Social Media'. 

The contents of this project are:

* events-training.txt - List of the used Upcoming.org events to train the used classifiers. For each event, the Upcoming id, Upcoming semantic type and the ids of the associated Flickr photos are given. Metadata of these Flickr photos can be crawled using the Flickr API: http://www.flickr.com/services/api/explore/flickr.photos.getInfo
* events-test.txt - List of the used Upcoming.org events to evaluate our proposed methodology. The data is structured in the same way as events-training.txt.
* entities-training.txt - The mentions of ambigious names in the text of the events in events-training.txt which are mapped to entities registered in the YAGO2 knowledge base, using the AIDA framework. For each mention, the mapped entity, mention-entity similarity and the semantic type of the entity are given. 
* entities-test.txt - The mentions of ambigious names in the text of the events in events-test.txt which are mapped to entities registered in the YAGO2 knowledge base, using the AIDA framework.
* features-nearest-documents-training.txt - More than 60 million geotagged Flickr photos are used to construct the nearest-documents feature vectors of the events. It would take a very long time to crawl them using the Flickr API, given their ids. Therefore, we put this file available which contains the nearest-documents feature vectors of the events in events-training.txt.
* features-nearest-documents-test.txt - The nearest-documents feature vectors of the events in events-test.txt.

###Questions
This paper is under a double-blind reviewing process. Our contact information will be added after the paper is accepted.