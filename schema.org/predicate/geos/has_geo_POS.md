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

title: has_geo_location_has_POS
linkTitle: has_geo_location_has_POS

keywords: [has_POS]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/geo

aliases:
- has-pos
- has_POS
- hasPOS
- has_geo_location_has_POS
---

Predicate to describe the geo of Organization, Person.

Use it like this: 
- [ #has_/geo/_POS :: Place ] or 
- [ has_geo_has_POS :: Place ] 

Points-of-Sales operated by the organization or person.

Predicate describes that: 
[ #has_/domain  :: Organization, Person ]
( #has_/name :: has_geo_location_has_POS )
( #has_/range :: Place )

