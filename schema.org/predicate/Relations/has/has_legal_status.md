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
title: has_legal_status

linkTitle: has_legal_status
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
- legal-status
- legal_status
- legalStatus
- has_legal_status
---

Use it like this: 
- [ #has/_legal_status :: DrugLegalStatus, MedicalEnumeration, Text] or 
- [ has_legal_status :: DrugLegalStatus, MedicalEnumeration, Text] 

The drug or supplement&#x27;s legal status, including any controlled substance schedules that apply.

Relation describes that: 
[ #has_/domain  :: DietarySupplement, Drug, MedicalEntity]
( #has_/name :: is_legal_status)
( #has_/range :: DrugLegalStatus, MedicalEnumeration, Text)

