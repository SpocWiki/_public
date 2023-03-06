---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate geo
publish: true

# Hugo Tags
type: Pred_geo

title: has_geo_location_course
linkTitle: has_geo_location_course

keywords: [course]
layout: 
draft: false
publishDate:
expiryDate: 

superseded_by: exerciseCourse

tags:
- schema.org/Predicate/geo

aliases:
- course
- course
- course
- has_geo_location_course
---

Predicate to describe the geo of ExerciseAction.

Use it like this: 
- [ #has_/geo/_course :: Place ] or 
- [ has_geo_course :: Place ] 

A sub property of location. The course where this action was taken.

Predicate describes that: 
[ #has_/domain  :: ExerciseAction ]
( #has_/name :: has_geo_location_course )
( #has_/range :: Place )

[ #is_/sub_property_of  :: location ]

