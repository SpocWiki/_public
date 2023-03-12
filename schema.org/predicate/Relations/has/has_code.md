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
title: has_code

linkTitle: has_code
keywords: [code]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- code
- code
- code
- has_code
- has_abbreviation
---

Use it like this: 
- [ #has/_code :: MedicalCode ] or 
- [ has_code :: MedicalCode ] 

A medical code for the entity, taken from a controlled vocabulary or ontology such as ICD-9, DiseasesDB, MeSH, SNOMED-CT, RxNorm, etc.

Also used for all other Codes and Abbreviations. 

Relation describes that: 
[ #has_/domain  :: [[../../../Type/is_a_thing/medical_entity]] ]
( #has_/name :: has_code )
( #has_/range :: [[medical_code]] )

