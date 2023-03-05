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
title: has_preparation

linkTitle: has_preparation
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
- preparation
- preparation
- preparation
- has_preparation
---

Use it like this: 
- [ #has/_preparation :: MedicalEntity, Text] or 
- [ has_preparation :: MedicalEntity, Text] 

Typical preparation that a patient must undergo before having the procedure performed.

Relation describes that: 
[ #has_/domain  :: MedicalProcedure]
( #has_/name :: is_preparation)
( #has_/range :: MedicalEntity, Text)

