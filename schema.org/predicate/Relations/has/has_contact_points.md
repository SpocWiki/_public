---
license: CC BY-SA 4.0
confidential: public
isDeleted: true
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Relation
publish: false

# Hugo Tags
type: Predi_Relation
title: has_contact_points

linkTitle: has_contact_points
keywords: [contact, points]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- contact-points
- contact_points
- contactPoints
- has_contact_points
---

[ superseded_by :: contactPoint ]

Use it like this: 
- [ #has/_contact_point :: ContactPoint ] or 
- [ has_contact_point :: ContactPoint ] 

A contact point for a person or organization.

Relation describes that: 
[ #has_/domain  :: Organization, Person ]
( #has_/name :: has_contact_point )
( #has_/range :: ContactPoint )

