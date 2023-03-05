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
title: has_program_prerequisites

linkTitle: has_program_prerequisites
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
- program-prerequisites
- program_prerequisites
- programPrerequisites
- has_program_prerequisites
---

[ #is_/part_of :: pending:]

Use it like this: 
- [ #has/_program_prerequisites :: AlignmentObject, Course, EducationalOccupationalCredential, Text] or 
- [ has_program_prerequisites :: AlignmentObject, Course, EducationalOccupationalCredential, Text] 

Prerequisites for enrolling in the program.

Relation describes that: 
[ #has_/domain  :: EducationalOccupationalProgram]
( #has_/name :: is_program_prerequisites)
( #has_/range :: AlignmentObject, Course, EducationalOccupationalCredential, Text)

