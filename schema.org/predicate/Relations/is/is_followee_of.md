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
title: is_followee_of

linkTitle: is_followee_of
keywords: [followee]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- followee
- is_followee_of
---

Use it like this: 
- [ #is/_followee_of :: Organization, Person ] or 
- [ is_followee_of :: Organization, Person ] 

A sub property of object. The person or organization being followed.

Relation describes that: 
[ #has_/domain  :: FollowAction ]
( #has_/name :: is_followee_of )
( #has_/range :: Organization, Person )

[ #is_/sub_property_of  :: object ]

