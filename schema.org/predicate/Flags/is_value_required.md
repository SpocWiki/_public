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

title: is_value_required
linkTitle: is_value_required

keywords: [value_required]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/True

aliases:
- value-required
- value_required
- valueRequired
- is_value_required
---

Use these simple Tags to mark Instances as True or False: 
#is_/_/value_required 
#is_/not/value_required 

Or write it as a Triple: 
[ is_value_required :: Boolean ] 

Whether the property must be filled in to complete the action.  Default is false.

Predicate describes that: 
[ #has_/domain  :: PropertyValueSpecification ]
( #has_/name :: is_value_required )
( #has_/range :: Boolean )

