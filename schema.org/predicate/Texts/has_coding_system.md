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

title: has_text_about_coding_system
linkTitle: has_text_about_coding_system

keywords: [coding, system]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- coding-system
- coding_system
- codingSystem
- has_text_about_coding_system
---

Predicate to describe the Text of MedicalCode.

Use it like this: 
- [ #has_/text/_about_coding_system :: Text ] or 
- [ has_text_about_coding_system :: Text ] 

The coding system, e.g. "ICD-10".

Predicated describes that: 
[ #has_/domain  :: MedicalCode ]
( #has_/name :: has_text_about_coding_system )
( #has_/range :: Text )

