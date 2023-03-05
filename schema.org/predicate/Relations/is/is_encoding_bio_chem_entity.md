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
title: is_encoding_bio_chem_entity

linkTitle: is_encoding_bio_chem_entity
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- encodes-bio-chem-entity
- encoding_bio_chem_entity
- encodesBioChemEntity
- is_encoding_bio_chem_entity
---

[ #is_/part_of :: pending:]

Use it like this: 
- [ #is/_encoding_bio_chem_entity :: BioChemEntity] or 
- [ is_encoding_bio_chem_entity :: BioChemEntity] 

Another BioChemEntity encoded by this one.

Relation describes that: 
[ #has_/domain  :: Gene]
( #has_/name :: is_encoding_bio_chem_entity)
( #has_/range :: BioChemEntity)

[ #is_/inverse_of  :: isEncodedByBioChemEntity]

