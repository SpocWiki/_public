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
title: has_variable_measured

linkTitle: has_variable_measured
keywords: [variable, measured]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- variable-measured
- variable_measured
- variableMeasured
- has_variable_measured
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_variable_measured :: PropertyValue, Text ] or 
- [ has_variable_measured :: PropertyValue, Text ] 

The variableMeasured property can indicate (repeated as necessary) the  variables that are measured in some dataset, either described as text or as pairs of identifier and description using PropertyValue.

Relation describes that: 
[ #has_/domain  :: Dataset ]
( #has_/name :: is_variable_measured )
( #has_/range :: PropertyValue, Text )

