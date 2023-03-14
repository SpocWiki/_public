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
title: is_legislation_transpose_of

linkTitle: is_legislation_transpose_of
keywords: [legislation, transposes]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- legislation-transposes
- legislation_transpose_of
- legislationTransposes
- is_legislation_transpose_of
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #is/_legislation_transpose_of :: Legislation ] or 
- [ is_legislation_transpose_of :: Legislation ] 

Indicates that this legislation (or part of legislation) fulfills the objectives set by another legislation,
by passing appropriate implementation measures.

Typically, some legislations of European Union's member states or regions transpose European Directives.
This indicates a legally binding link between the 2 legislations.

Relation describes that: 
[ #has_/domain  :: Legislation ]
( #has_/name :: is_legislation_transpose_of )
( #has_/range :: Legislation )

[ #is_/sub_property_of  :: legislationApplies ]

