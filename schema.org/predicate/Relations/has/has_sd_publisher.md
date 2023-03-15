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
title: has_sd_publisher

linkTitle: has_sd_publisher
keywords: [sd, publisher]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- sd-publisher
- sd_publisher
- sdPublisher
- has_sd_publisher
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_sd_publisher :: Organization, Person ] or 
- [ has_sd_publisher :: Organization, Person ] 

Indicates the party responsible for generating and publishing the current structured data markup, typically in cases where the structured data is derived automatically from existing published content but published on a different site. For example, student projects and open data initiatives often re-publish existing content with more explicitly structured metadata. The
[[sdPublisher]] property helps make such practices more explicit.

Relation describes that: 
[ #has_/domain  :: CreativeWork ]
( #has_/name :: is_sd_publisher )
( #has_/range :: Organization, Person )

