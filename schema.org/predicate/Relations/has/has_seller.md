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
title: has_seller

linkTitle: has_seller
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: merchant, vendor
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- seller
- seller
- seller
- has_seller
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_seller :: Organization, Person] or 
- [ has_seller :: Organization, Person] 

An entity which offers (sells / leases / lends / loans) the services / goods.  A seller may also be a provider.

Relation describes that: 
[ #has_/domain  :: BuyAction, Demand, Flight, Offer, Order]
( #has_/name :: is_seller)
( #has_/range :: Organization, Person)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: participant]

[ #has_/sub_properties :: ]
