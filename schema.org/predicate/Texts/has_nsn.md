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

title: has_text_about_nsn
linkTitle: has_text_about_nsn

keywords: [nsn]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- nsn
- nsn
- nsn
- has_text_about_nsn
---

Predicate to describe the Text of Product.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_nsn :: Text ] or 
- [ has_text_about_nsn :: Text ] 

Indicates the [NATO stock number](https://en.wikipedia.org/wiki/NATO_Stock_Number) (nsn) of a [[Product]].

Predicated describes that: 
[ #has_/domain  :: Product ]
( #has_/name :: has_text_about_nsn )
( #has_/range :: Text )

[ #is_/sub_property_of  :: identifier ]

