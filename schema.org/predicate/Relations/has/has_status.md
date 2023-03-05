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
title: has_status

linkTitle: has_status
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
- status
- status
- status
- has_status
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_status :: EventStatusType, MedicalStudyStatus, Text] or 
- [ has_status :: EventStatusType, MedicalStudyStatus, Text] 

The status of the study (enumerated).

Relation describes that: 
[ #has_/domain  :: MedicalCondition, MedicalProcedure, MedicalStudy]
( #has_/name :: is_status)
( #has_/range :: EventStatusType, MedicalStudyStatus, Text)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]

