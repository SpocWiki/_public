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

title: has_text_about_in_ch_i_key
linkTitle: has_text_about_in_ch_i_key

keywords: [in, ch, i, key]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- in-ch-i-key
- in_ch_i_key
- inChIKey
- has_text_about_in_ch_i_key
---

Predicate to describe the Text of MolecularEntity.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_in_ch_i_key :: Text ] or 
- [ has_text_about_in_ch_i_key :: Text ] 

InChIKey is a hashed version of the full InChI (using the SHA-256 algorithm).

Predicated describes that: 
[ #has_/domain  :: MolecularEntity ]
( #has_/name :: has_text_about_in_ch_i_key )
( #has_/range :: Text )

[ #is_/sub_property_of  :: hasRepresentation ]

