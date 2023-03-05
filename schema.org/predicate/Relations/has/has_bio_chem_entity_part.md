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
title: has_bio_chem_entity_part

linkTitle: has_bio_chem_entity_part
keywords: [bio, chem, entity, part]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- has-bio-chem-entity-part
- bio_chem_entity_part
- hasBioChemEntityPart
- has_bio_chem_entity_part
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_bio_chem_entity_part :: BioChemEntity ] or 
- [ has_bio_chem_entity_part :: BioChemEntity ] 

Indicates a BioChemEntity that (in some sense) has this BioChemEntity as a part.

Relation describes that: 
[ #has_/domain  :: BioChemEntity ]
( #has_/name :: is_bio_chem_entity_part )
( #has_/range :: BioChemEntity )

[ #is_/inverse_of  :: isPartOfBioChemEntity ]

