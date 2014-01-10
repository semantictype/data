event data
====

This data is used to evaluate our methodology which discovers the semantic type of events based on the context of their associated social media documents. Please, refer to our work when you use this data.

The contents of this project are:

* events-training.txt - List of the used Upcoming.org events to train the used classifiers. For each event, the Upcoming id, Upcoming semantic type and the ids of the associated Flickr photos are given. Metadata of these Flickr photos can be crawled using the Flickr API: http://www.flickr.com/services/api/explore/flickr.photos.getInfo
* events-test.txt - List the of used Upcoming.org events to evaluate our proposed methodology. The data is structured in the same way as events-training.txt.
* entities-training.txt - The mentions of ambigious names in the text of the events in events-training.txt which are mapped to entities registered in the YAGO2 knowledge base, using the AIDA framework. For each mention, the mapped entity, mention-entity similarity and the semantic type of the entity are given. 
* entities-test.txt - The mentions of ambigious names in the text of the events in events-test.txt which are mapped to entities registered in the YAGO2 knowledge base, using the AIDA framework.
* features-nearest-documents-training.txt - More than 23.3 million geotagged Flickr photos are used to construct the nearest-documents representations of the events. It would take a very long time to crawl them using the Flickr API, given their ids. Therefore, we put this file available which contains the nearest-documents feature vectors of the events in events-training.txt. The feature vectors are formatted using the WEKA standard.
* features-nearest-documents-test.txt - The nearest-documents feature vectors of the events in events-test.txt.

###Questions
In case you have any questions, feel free to contact me.
