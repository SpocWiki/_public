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
title: is_performer_in

linkTitle: is_performer_in
keywords: [performer, in]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- performer-in
- performer_in
- performerIn
- is_performer_in
---

Use it like this: 
- [ #is/_performer_in :: Event ] or 
- [ is_performer_in :: Event ] 

Event that this person is a performer or participant in.

Relation describes that: 
[ #has_/domain  :: Person ]
( #has_/name :: is_performer_in )
( #has_/range :: Event )

[ #is/_inverse_of  :: [[has_performer]] ]

