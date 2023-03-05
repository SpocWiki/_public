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

title: has_text_about_post_op
linkTitle: has_text_about_post_op

keywords: [post, op]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- post-op
- post_op
- postOp
- has_text_about_post_op
---

Predicate to describe the Text of MedicalDevice.

Use it like this: 
- [ #has_/text/_about_post_op :: Text ] or 
- [ has_text_about_post_op :: Text ] 

A description of the postoperative procedures, care, and/or followups for this device.

Predicated describes that: 
[ #has_/domain  :: MedicalDevice ]
( #has_/name :: is_post_op )
( #has_/range :: Text )

