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
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- sd-publisher
- sd_publisher
- sdPublisher
- has_sd_publisher
---

[ #is_/part_of :: pending:]

Use it like this: 
- [ #has/_sd_publisher :: Organization, Person] or 
- [ has_sd_publisher :: Organization, Person] 

Indicates the party responsible for generating and publishing the current structured data markup, typically in cases where the structured data is derived automatically from existing published content but published on a different site. For example, student projects and open data initiatives often re-publish existing content with more explicitly structured metadata. The
&lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/sdPublisher&quot;&gt;sdPublisher&lt;/a&gt; property helps make such practices more explicit.

Relation describes that: 
[ #has_/domain  :: CreativeWork]
( #has_/name :: is_sd_publisher)
( #has_/range :: Organization, Person)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]
