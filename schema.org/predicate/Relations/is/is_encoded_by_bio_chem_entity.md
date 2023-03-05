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
title: is_encoded_by_bio_chem_entity

linkTitle: is_encoded_by_bio_chem_entity
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
- is-encoded-by-bio-chem-entity
- encoded_by_bio_chem_entity
- isEncodedByBioChemEntity
- is_encoded_by_bio_chem_entity
---

[ #is_/part_of :: pending:]

Use it like this: 
- [ #is/_encoded_by_bio_chem_entity :: Gene] or 
- [ is_encoded_by_bio_chem_entity :: Gene] 

Another BioChemEntity encoding by this one.

Relation describes that: 
[ #has_/domain  :: BioChemEntity]
( #has_/name :: is_encoded_by_bio_chem_entity)
( #has_/range :: Gene)

[ #is_/inverse_of  :: encodesBioChemEntity]

