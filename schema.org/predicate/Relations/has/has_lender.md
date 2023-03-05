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
title: has_lender

linkTitle: has_lender
keywords: [lender]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- lender
- lender
- lender
- has_lender
---

Use it like this: 
- [ #has/_lender :: Organization, Person ] or 
- [ has_lender :: Organization, Person ] 

A sub property of participant. The person that lends the object being borrowed.

Relation describes that: 
[ #has_/domain  :: BorrowAction ]
( #has_/name :: is_lender )
( #has_/range :: Organization, Person )

[ #is_/sub_property_of  :: participant ]

