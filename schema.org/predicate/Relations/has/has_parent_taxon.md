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
title: has_parent_taxon

linkTitle: has_parent_taxon
keywords: [parent, taxon]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- parent-taxon
- parent_taxon
- parentTaxon
- has_parent_taxon
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_parent_taxon :: Taxon, Text, URL ] or 
- [ has_parent_taxon :: Taxon, Text, URL ] 

Closest parent taxon of the taxon in question.

Relation describes that: 
[ #has_/domain  :: Taxon ]
( #has_/name :: is_parent_taxon )
( #has_/range :: Taxon, Text, URL )

[ #is_/inverse_of  :: childTaxon ]

