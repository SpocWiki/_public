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
title: has_jurisdiction

linkTitle: has_jurisdiction
keywords: [jurisdiction]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- jurisdiction
- jurisdiction
- jurisdiction
- has_jurisdiction
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_jurisdiction :: AdministrativeArea, Text ] or 
- [ has_jurisdiction :: AdministrativeArea, Text ] 

Indicates a legal jurisdiction, e.g. of some legislation, or where some government service is based.

Relation describes that: 
[ #has_/domain  :: GovernmentService, Legislation ]
( #has_/name :: has_jurisdiction )
( #has_/range :: AdministrativeArea, Text )

[ #has_/sub_properties :: [ legislationJurisdiction ] ]

