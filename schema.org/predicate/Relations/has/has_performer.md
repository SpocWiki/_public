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
title: has_performer

linkTitle: has_performer
keywords: [performer]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: performers

tags:
- schema.org/Predicate/Relation

aliases:
- performer
- has_performer
---

Use it like this: 
- [ #has/_performer :: Organization, Person ] or 
- [ has_performer :: Organization, Person ] 

A performer at the event&amp;#x2014;for example, a presenter, musician, musical group or actor.

Relation describes that: 
[ #has_/domain  :: Event ]
( #has_/name :: has_performer )
( #has_/range :: Organization, Person )

[ #is/_inverse_of  :: [[is_performer_in]] ]

[[../is_inverse_of]]

[[../is_inverse_of]]
