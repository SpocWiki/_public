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

title: is_multiple_value
linkTitle: is_multiple_value

keywords: [multiple_value]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/True

aliases:
- multiple-value
- multiple_value
- multipleValues
- is_multiple_value
---

Use these simple Tags to mark Instances as True or False: 
#is_/_/multiple_value 
#is_/not_/multiple_value 

Or write it as a Triple: 
[ is_multiple_value :: Boolean ] 

Whether multiple values are allowed for the property.  Default is false.

Predicate describes that: 
[ #has_/domain  :: PropertyValueSpecification ]
( #has_/name :: is_multiple_value )
( #has_/range :: Boolean )

