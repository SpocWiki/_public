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
title: has_area_served

linkTitle: has_area_served
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: serviceArea
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- area-served
- area_served
- areaServed
- has_area_served
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_area_served :: AdministrativeArea, GeoShape, Place, Text] or 
- [ has_area_served :: AdministrativeArea, GeoShape, Place, Text] 

The geographic area where a service or offered item is provided.

Relation describes that: 
[ #has_/domain  :: ContactPoint, DeliveryChargeSpecification, Demand, Offer, Organization, Service]
( #has_/name :: is_area_served)
( #has_/range :: AdministrativeArea, GeoShape, Place, Text)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: availableAtOrFrom, eligibleRegion]

