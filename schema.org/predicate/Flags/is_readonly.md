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

title: is_readonly
linkTitle: is_readonly

keywords: [readonly]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/True

aliases:
- readonly-value
- readonly
- readonlyValue
- is_readonly
---

Use these simple Tags to mark Instances as True or False: 
#is_/_/readonly 
#is_/not/readonly 

Or write it as a Triple: 
[ is_readonly :: Boolean ] 

Whether or not a property is mutable.  Default is false. Specifying this for a property that also has a value makes it act similar to a &quot;hidden&quot; input in an HTML form.

Predicate describes that: 
[ #has_/domain  :: PropertyValueSpecification ]
( #has_/name :: is_readonly )
( #has_/range :: Boolean )

