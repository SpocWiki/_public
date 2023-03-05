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
title: has_creator

linkTitle: has_creator
keywords: [creator]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- creator
- creator
- creator
- has_creator
---

Use it like this: 
- [ #has/_creator :: Organization, Person ] or 
- [ has_creator :: Organization, Person ] 

The creator/author of this CreativeWork. This is the same as the Author property for CreativeWork.

Relation describes that: 
[ #has_/domain  :: CreativeWork, UserComments ]
( #has_/name :: is_creator )
( #has_/range :: Organization, Person )

[ #has_/sub_properties :: [ legislationPassedBy ] ]

