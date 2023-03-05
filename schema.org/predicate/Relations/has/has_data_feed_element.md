---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Relation
publish: true

# Hugo Tags
type: Predi_Relation
title: has_data_feed_element

linkTitle: has_data_feed_element
keywords: [data, feed, element]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- data-feed-element
- data_feed_element
- dataFeedElement
- has_data_feed_element
---

Use it like this: 
- [ #has/_data_feed_element :: DataFeedItem, Text, Thing ] or 
- [ has_data_feed_element :: DataFeedItem, Text, Thing ] 

An item within a data feed. Data feeds may have many elements.

Relation describes that: 
[ #has_/domain  :: DataFeed ]
( #has_/name :: is_data_feed_element )
( #has_/range :: DataFeedItem, Text, Thing )

