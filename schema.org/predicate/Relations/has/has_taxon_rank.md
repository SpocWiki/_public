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
title: has_taxon_rank

linkTitle: has_taxon_rank
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- taxon-rank
- taxon_rank
- taxonRank
- has_taxon_rank
---

[ #is_/part_of :: pending:]

Use it like this: 
- [ #has/_taxon_rank :: PropertyValue, Text, URL] or 
- [ has_taxon_rank :: PropertyValue, Text, URL] 

The taxonomic rank of this taxon given preferably as a URI from a controlled vocabulary � typically the ranks from TDWG TaxonRank ontology or equivalent Wikidata URIs.

Relation describes that: 
[ #has_/domain  :: Taxon]
( #has_/name :: is_taxon_rank)
( #has_/range :: PropertyValue, Text, URL)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]
