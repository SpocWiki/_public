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
title: is_affected_by

linkTitle: is_affected_by
keywords: [affected, by]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- affected-by
- affected_by
- affectedBy
- is_affected_by
---

Use it like this: 
- [ #is/_affected_by :: Drug ] or 
- [ is_affected_by :: Drug ] 

Drugs that affect the test's results.

Relation describes that: 
[ #has_/domain  :: MedicalTest ]
( #has_/name :: is_affected_by )
( #has_/range :: Drug )

