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
title: has_child_taxon

linkTitle: has_child_taxon
keywords: [child, taxon]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- child-taxon
- child_taxon
- childTaxon
- has_child_taxon
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_child_taxon :: Taxon, Text, URL ] or 
- [ has_child_taxon :: Taxon, Text, URL ] 

Closest child taxa of the taxon in question.

Relation describes that: 
[ #has_/domain  :: Taxon ]
( #has_/name :: is_child_taxon )
( #has_/range :: Taxon, Text, URL )

[ #is_/inverse_of  :: parentTaxon ]

