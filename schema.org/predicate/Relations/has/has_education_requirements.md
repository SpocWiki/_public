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
title: has_education_requirements

linkTitle: has_education_requirements
keywords: [education, requirements]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- education-requirements
- education_requirements
- educationRequirements
- has_education_requirements
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_education_requirements :: EducationalOccupationalCredential, Text ] or 
- [ has_education_requirements :: EducationalOccupationalCredential, Text ] 

Educational background needed for the position or Occupation.

Relation describes that: 
[ #has_/domain  :: JobPosting, Occupation ]
( #has_/name :: is_education_requirements )
( #has_/range :: EducationalOccupationalCredential, Text )

