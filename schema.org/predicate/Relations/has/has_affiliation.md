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
title: has_affiliation

linkTitle: has_affiliation
keywords: [affiliation]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- affiliation
- affiliation
- affiliation
- has_affiliation
---

Use it like this: 
- [ #has/_affiliation :: Organization ] or 
- [ has_affiliation :: Organization ] 

An organization that this person is affiliated with. For example, a school/university, a club, or a team.

Relation describes that: 
[ #has_/domain  :: Person ]
( #has_/name :: has_affiliation )
( #has_/range :: Organization )

[ #is_/sub_property_of  :: memberOf ]

