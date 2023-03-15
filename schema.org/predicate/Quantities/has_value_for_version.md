---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Quantity
publish: true

# Hugo Tags
type: Predi_Quantity

title: has_version
linkTitle: has_version

keywords: [version]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Quantity

aliases:
- version
- version
- version
- has_value_for_version
---

Predicate to describe the Quantity of CreativeWork.

Use it like this: 
- [ #has_/value/_for_version :: Number, Text ] or 
- [ has_value_for_version :: Number, Text ] 

The version of the CreativeWork embodied by a specified resource.

Predicate describes that: 
[ #has_/domain  :: CreativeWork ]
( #has_/name :: has_value_for_version )
( #has_/range :: Number, Text )

