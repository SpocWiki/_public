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
title: has_main_entity_of_page

linkTitle: has_main_entity_of_page
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
- main-entity-of-page
- main_entity_of_page
- mainEntityOfPage
- has_main_entity_of_page
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_main_entity_of_page :: CreativeWork, URL] or 
- [ has_main_entity_of_page :: CreativeWork, URL] 

Indicates a page (or other CreativeWork) for which this thing is the main entity being described. See &lt;a href&#x3D;&quot;/docs/datamodel.html#mainEntityBackground&quot;&gt;background notes&lt;/a&gt; for details.

Relation describes that: 
[ #has_/domain  :: Thing]
( #has_/name :: is_main_entity_of_page)
( #has_/range :: CreativeWork, URL)

[ #is_/inverse_of  :: mainEntity]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]

