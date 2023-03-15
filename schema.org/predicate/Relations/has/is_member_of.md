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
title: is_member_of

linkTitle: is_member_of
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
- is_member_of
---

Use it like this: 
- [ #is/_member_of :: [[../../../Type/is_a_/organization]], [[../../../Type/is_a_/intangible/program_membership]] ] or 
- [ is_member_of :: [[../../../Type/is_a_/organization]], [[../../../Type/is_a_/intangible/program_membership]] ] 

An [[../../../Type/is_a_/organization]] (or [[../../../Type/is_a_/intangible/program_membership]]) to which this Person or Organization belongs.

Relation describes that: 
[ #has_/domain  :: Organization, Person ]
( #has_/name :: is_member_of )
( #has_/range :: [[../../../Type/is_a_/organization]], [[../../../Type/is_a_/intangible/program_membership]] )

[ #is_/inverse_of  :: [[has_member]] ]

[ #has_/sub_properties :: [[has_affiliation_with]] ]

