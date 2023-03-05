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
title: has_amenity_feature

linkTitle: has_amenity_feature
keywords: [amenity, feature]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- amenity-feature
- amenity_feature
- amenityFeature
- has_amenity_feature
---

Use it like this: 
- [ #has/_amenity_feature :: LocationFeatureSpecification ] or 
- [ has_amenity_feature :: LocationFeatureSpecification ] 

An amenity feature (e.g. a characteristic or service) of the Accommodation. This generic property does not make a statement about whether the feature is included in an offer for the main accommodation or available at extra costs.

Relation describes that: 
[ #has_/domain  :: Accommodation, FloorPlan, LodgingBusiness, Place ]
( #has_/name :: is_amenity_feature )
( #has_/range :: LocationFeatureSpecification )

