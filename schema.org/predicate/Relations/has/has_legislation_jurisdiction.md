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
title: has_legislation_jurisdiction

linkTitle: has_legislation_jurisdiction
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
- has_legislation_jurisdiction
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_legislation_jurisdiction :: AdministrativeArea, Text ] or 
- [ has_legislation_jurisdiction :: AdministrativeArea, Text ] 

The jurisdiction from which the legislation originates.

Relation describes that: 
[ #has_/domain  :: Legislation ]
( #has_/name :: is_legislation_jurisdiction )
( #has_/range :: AdministrativeArea, Text )

[ #is_/sub_property_of  :: jurisdiction, spatialCoverage ]

