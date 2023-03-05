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
title: has_service_area

linkTitle: has_service_area
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: area
superseded_by: areaServed

tags:
- schema.org/Predicate/Relation

aliases:
- service-area
- service_area
- serviceArea
- has_service_area
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_service_area :: AdministrativeArea, GeoShape, Place] or 
- [ has_service_area :: AdministrativeArea, GeoShape, Place] 

The geographic area where the service is provided.

Relation describes that: 
[ #has_/domain  :: ContactPoint, Organization, Service]
( #has_/name :: is_service_area)
( #has_/range :: AdministrativeArea, GeoShape, Place)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]

