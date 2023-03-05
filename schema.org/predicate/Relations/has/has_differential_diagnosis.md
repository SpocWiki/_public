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
title: has_differential_diagnosis

linkTitle: has_differential_diagnosis
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
- differential-diagnosis
- differential_diagnosis
- differentialDiagnosis
- has_differential_diagnosis
---

Use it like this: 
- [ #has/_differential_diagnosis :: DDxElement] or 
- [ has_differential_diagnosis :: DDxElement] 

One of a set of differential diagnoses for the condition. Specifically, a closely-related or competing diagnosis typically considered later in the cognitive process whereby this medical condition is distinguished from others most likely responsible for a similar collection of signs and symptoms to reach the most parsimonious diagnosis or diagnoses in a patient.

Relation describes that: 
[ #has_/domain  :: MedicalCondition]
( #has_/name :: is_differential_diagnosis)
( #has_/range :: DDxElement)

