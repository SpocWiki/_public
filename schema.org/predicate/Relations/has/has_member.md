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
title: has_member

linkTitle: has_member
keywords: [member]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: members, musicGroupMember

tags:
- schema.org/Predicate/Relation

aliases:
- member
- member
- member
- has_member
---

Use it like this: 
- [ #has/_member :: Organization, Person ] or 
- [ has_member :: Organization, Person ] 

A member of an Organization or a ProgramMembership. Organizations can be members of organizations; ProgramMembership is typically for individuals.

Relation describes that: 
[ #has_/domain  :: Organization, ProgramMembership ]
( #has_/name :: is_member )
( #has_/range :: Organization, Person )

[ #is_/inverse_of  :: memberOf ]

