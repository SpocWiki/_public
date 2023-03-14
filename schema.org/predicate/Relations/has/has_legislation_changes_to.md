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
title: has_legislation_changes

linkTitle: has_legislation_changes
keywords: [legislation, changes]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- legislation-changes
- legislation_changes
- legislationChanges
- has_legislation_changes
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_legislation_changes :: Legislation ] or 
- [ has_legislation_changes :: Legislation ] 

Another legislation that this legislation changes. 

This encompasses the notions of amendment, replacement, correction, repeal, or other types of change.

This may be a direct change (textual or non-textual amendment) or a consequential or indirect change.

The property is to be used to express the existence of a change relationship between two acts
rather than the existence of a consolidated version of the text that shows the result of the change.

For consolidation relationships, use the [[legislation_Consolidates]] property.

Relation describes that: 
[ #has_/domain  :: Legislation ]
( #has_/name :: has_legislation_changes_to )
( #has_/range :: Legislation )

