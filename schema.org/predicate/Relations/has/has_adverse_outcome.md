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
title: has_adverse_outcome

linkTitle: has_adverse_outcome
keywords: [adverse, outcome]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- adverse-outcome
- adverse_outcome
- adverseOutcome
- has_adverse_outcome
---

Use it like this: 
- [ #has/_adverse_outcome :: MedicalEntity ] or 
- [ has_adverse_outcome :: MedicalEntity ] 

A possible complication and/or side effect of this therapy. If it is known that an adverse outcome is serious (resulting in death, disability, or permanent damage; requiring hospitalization; or otherwise life-threatening or requiring immediate medical attention), tag it as a seriousAdverseOutcome instead.

Relation describes that: 
[ #has_/domain  :: MedicalDevice, TherapeuticProcedure ]
( #has_/name :: is_adverse_outcome )
( #has_/range :: MedicalEntity )

