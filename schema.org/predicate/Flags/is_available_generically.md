---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Boolean
publish: true

# Hugo Tags
type: Pred_Bool

title: is_available_generically
linkTitle: is_available_generically

keywords: [available_generically]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/True

aliases:
- available-generically
- available_generically
- isAvailableGenerically
- is_available_generically
---

Use these simple Tags to mark Instances as True or False: 
#is_/_/available_generically 
#is_/not/available_generically 

Or write it as a Triple: 
[ is_available_generically :: Boolean ] 

True if the drug is available in a generic form (regardless of name).

Predicate describes that: 
[ #has_/domain  :: Drug ]
( #has_/name :: is_available_generically )
( #has_/range :: Boolean )

