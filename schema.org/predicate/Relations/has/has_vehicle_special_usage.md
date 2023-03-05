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
title: has_vehicle_special_usage

linkTitle: has_vehicle_special_usage
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
- vehicle-special-usage
- vehicle_special_usage
- vehicleSpecialUsage
- has_vehicle_special_usage
---

[ #is_/part_of :: https://auto.schema.org]

Use it like this: 
- [ #has/_vehicle_special_usage :: CarUsageType, Text] or 
- [ has_vehicle_special_usage :: CarUsageType, Text] 

Indicates whether the vehicle has been used for special purposes, like commercial rental, driving school, or as a taxi. The legislation in many countries requires this information to be revealed when offering a car for sale.

Relation describes that: 
[ #has_/domain  :: Vehicle]
( #has_/name :: is_vehicle_special_usage)
( #has_/range :: CarUsageType, Text)

