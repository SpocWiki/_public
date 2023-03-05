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

title: has_text_about_pre_op
linkTitle: has_text_about_pre_op

keywords: [pre, op]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- pre-op
- pre_op
- preOp
- has_text_about_pre_op
---

Predicate to describe the Text of MedicalDevice.

Use it like this: 
- [ #has_/text/_about_pre_op :: Text ] or 
- [ has_text_about_pre_op :: Text ] 

A description of the workup, testing, and other preparations required before implanting this device.

Predicated describes that: 
[ #has_/domain  :: MedicalDevice ]
( #has_/name :: has_text_about_pre_op )
( #has_/range :: Text )

