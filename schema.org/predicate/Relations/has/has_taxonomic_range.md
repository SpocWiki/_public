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
title: has_taxonomic_range

linkTitle: has_taxonomic_range
keywords: [taxonomic, range]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- taxonomic-range
- taxonomic_range
- taxonomicRange
- has_taxonomic_range
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_taxonomic_range :: DefinedTerm, Taxon, Text, URL ] or 
- [ has_taxonomic_range :: DefinedTerm, Taxon, Text, URL ] 

The taxonomic grouping of the organism that expresses, encodes, or in some way related to the BioChemEntity.

Relation describes that: 
[ #has_/domain  :: BioChemEntity ]
( #has_/name :: is_taxonomic_range )
( #has_/range :: DefinedTerm, Taxon, Text, URL )

