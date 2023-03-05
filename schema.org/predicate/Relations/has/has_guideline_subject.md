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
title: has_guideline_subject

linkTitle: has_guideline_subject
keywords: [guideline, subject]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- guideline-subject
- guideline_subject
- guidelineSubject
- has_guideline_subject
---

Use it like this: 
- [ #has/_guideline_subject :: MedicalEntity ] or 
- [ has_guideline_subject :: MedicalEntity ] 

The medical conditions, treatments, etc. that are the subject of the guideline.

Relation describes that: 
[ #has_/domain  :: MedicalGuideline ]
( #has_/name :: is_guideline_subject )
( #has_/range :: MedicalEntity )

