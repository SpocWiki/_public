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

title: has_text_about_iupac_name
linkTitle: has_text_about_iupac_name

keywords: [iupac, name]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- iupac-name
- iupac_name
- iupacName
- has_text_about_iupac_name
---

Predicate to describe the Text of MolecularEntity.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_iupac_name :: Text ] or 
- [ has_text_about_iupac_name :: Text ] 

Systematic method of naming chemical compounds as recommended by the International Union of Pure and Applied Chemistry (IUPAC).

Predicated describes that: 
[ #has_/domain  :: MolecularEntity ]
( #has_/name :: is_iupac_name )
( #has_/range :: Text )

