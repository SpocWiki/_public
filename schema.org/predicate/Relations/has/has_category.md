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
title: has_category

linkTitle: has_category
keywords: [category]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- category
- category
- category
- has_category
---

Use it like this: 
- [ #has/_category :: CategoryCode, PhysicalActivityCategory, Text, Thing, URL ] or 
- [ has_category :: CategoryCode, PhysicalActivityCategory, Text, Thing, URL ] 

A category for the item. Greater signs or slashes can be used to informally indicate a category hierarchy.

Relation describes that: 
[ #has_/domain  :: ActionAccessSpecification, Invoice, Offer, PhysicalActivity, Product, Recommendation, Service, SpecialAnnouncement ]
( #has_/name :: is_category )
( #has_/range :: CategoryCode, PhysicalActivityCategory, Text, Thing, URL )

[ #has_/sub_properties :: [ accommodationCategory ] ]

