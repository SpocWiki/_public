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
title: has_fuel_type

linkTitle: has_fuel_type
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
- fuel-type
- fuel_type
- fuelType
- has_fuel_type
---

Use it like this: 
- [ #has/_fuel_type :: QualitativeValue, Text, URL] or 
- [ has_fuel_type :: QualitativeValue, Text, URL] 

The type of fuel suitable for the engine or engines of the vehicle. If the vehicle has only one engine, this property can be attached directly to the vehicle.

Relation describes that: 
[ #has_/domain  :: EngineSpecification, Vehicle]
( #has_/name :: is_fuel_type)
( #has_/range :: QualitativeValue, Text, URL)

