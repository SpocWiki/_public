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
title: is_legislation_jurisdiction_of

linkTitle: is_legislation_jurisdiction_of
keywords: [legislation, jurisdiction]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- legislation-jurisdiction
- legislation_jurisdiction
- legislationJurisdiction
- is_legislation_jurisdiction_of
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #is/_legislation_jurisdiction_of :: AdministrativeArea, Text ] or 
- [ is_legislation_jurisdiction_of :: AdministrativeArea, Text ] 

The jurisdiction from which the legislation originates.

Relation describes that: 
[ #has_/domain  :: Legislation ]
( #has_/name :: is_legislation_jurisdiction_of )
( #has_/range :: AdministrativeArea, Text )

[ #is_/sub_property_of  :: jurisdiction, spatialCoverage ]

