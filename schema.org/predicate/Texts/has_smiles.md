---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Text
publish: true

# Hugo Tags
type: Pred_Text

title: has_text_about_smiles
linkTitle: has_text_about_smiles

keywords: [smiles]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- smiles
- smiles
- smiles
- has_text_about_smiles
---

Predicate to describe the Text of MolecularEntity.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_smiles :: Text ] or 
- [ has_text_about_smiles :: Text ] 

A specification in form of a line notation for describing the structure of chemical species using short ASCII strings.  Double bond stereochemistry \ indicators may need to be escaped in the string in formats where the backslash is an escape character.

Predicated describes that: 
[ #has_/domain  :: MolecularEntity ]
( #has_/name :: is_smiles )
( #has_/range :: Text )

[ #is_/sub_property_of  :: hasRepresentation ]

