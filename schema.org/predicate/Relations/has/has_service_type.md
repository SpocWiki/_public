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
title: has_service_type

linkTitle: has_service_type
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
- service-type
- service_type
- serviceType
- has_service_type
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_service_type :: GovernmentBenefitsType, Text] or 
- [ has_service_type :: GovernmentBenefitsType, Text] 

The type of service being offered, e.g. veterans&#x27; benefits, emergency relief, etc.

Relation describes that: 
[ #has_/domain  :: Service]
( #has_/name :: is_service_type)
( #has_/range :: GovernmentBenefitsType, Text)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]

