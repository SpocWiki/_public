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
title: has_comprised_of

linkTitle: has_comprised_of
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
- comprised-of
- comprised_of
- comprisedOf
- has_comprised_of
---

Use it like this: 
- [ #has/_comprised_of :: AnatomicalStructure, AnatomicalSystem] or 
- [ has_comprised_of :: AnatomicalStructure, AnatomicalSystem] 

Specifying something physically contained by something else. Typically used here for the underlying anatomical structures, such as organs, that comprise the anatomical system.

Relation describes that: 
[ #has_/domain  :: AnatomicalSystem]
( #has_/name :: is_comprised_of)
( #has_/range :: AnatomicalStructure, AnatomicalSystem)

