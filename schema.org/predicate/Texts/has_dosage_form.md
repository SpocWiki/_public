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

title: has_text_about_dosage_form
linkTitle: has_text_about_dosage_form

keywords: [dosage, form]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- dosage-form
- dosage_form
- dosageForm
- has_text_about_dosage_form
---

Predicate to describe the Text of Drug.

Use it like this: 
- [ #has_/text/_about_dosage_form :: Text ] or 
- [ has_text_about_dosage_form :: Text ] 

A dosage form in which this drug/supplement is available, e.g. "tablet", "suspension", "injection".

Predicated describes that: 
[ #has_/domain  :: Drug ]
( #has_/name :: has_text_about_dosage_form )
( #has_/range :: Text )

