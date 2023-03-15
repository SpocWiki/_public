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
title: is_owning

linkTitle: is_owning
keywords: [owns]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- owns
- is_owning
---

Use it like this: 
- [ #is/_owning :: OwnershipInfo, Product ] or 
- [ is_owning :: OwnershipInfo, Product ] 

Products owned by the organization or person.

Relation describes that: 
[ #has_/domain  :: Organization, Person ]
( #has_/name :: is_owning )
( #has_/range :: OwnershipInfo, Product )

