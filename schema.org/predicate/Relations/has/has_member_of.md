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
title: has_member_of

linkTitle: has_member_of
keywords: [member, of]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- member-of
- member_of
- memberOf
- has_member_of
---

Use it like this: 
- [ #has/_member_of :: Organization, ProgramMembership ] or 
- [ has_member_of :: Organization, ProgramMembership ] 

An Organization (or ProgramMembership) to which this Person or Organization belongs.

Relation describes that: 
[ #has_/domain  :: Organization, Person ]
( #has_/name :: is_member_of )
( #has_/range :: Organization, ProgramMembership )

[ #is_/inverse_of  :: member ]

[ #has_/sub_properties :: [ affiliation ] ]

