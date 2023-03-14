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
title: has_itinerary

linkTitle: has_itinerary
keywords: [itinerary]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- itinerary
- itinerary
- itinerary
- has_itinerary
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_itinerary :: ItemList, Place ] or 
- [ has_itinerary :: ItemList, Place ] 

Destination(s) ( &lt;a class="localLink" href="/Place"&gt;Place&lt;/a&gt; ) that make up a trip. For a trip where destination order is important use &lt;a class="localLink" href="/ItemList"&gt;ItemList&lt;/a&gt; to specify that order (see examples).

Relation describes that: 
[ #has_/domain  :: Trip ]
( #has_/name :: has_itinerary )
( #has_/range :: ItemList, Place )

