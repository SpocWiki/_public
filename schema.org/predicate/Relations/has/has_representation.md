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
title: has_representation

linkTitle: has_representation
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- has-representation
- representation
- hasRepresentation
- has_representation
---

[ #is_/part_of :: pending:]

Use it like this: 
- [ #has/_representation :: PropertyValue, Text, URL] or 
- [ has_representation :: PropertyValue, Text, URL] 

A common representation such as a protein sequence or chemical structure for this entity. For images use schema.org/image.

Relation describes that: 
[ #has_/domain  :: BioChemEntity]
( #has_/name :: is_representation)
( #has_/range :: PropertyValue, Text, URL)

[ #has_/sub_properties :: hasBioPolymerSequence, inChI, inChIKey, smiles]

