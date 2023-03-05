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

title: has_text_about_dose_unit
linkTitle: has_text_about_dose_unit

keywords: [dose, unit]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- dose-unit
- dose_unit
- doseUnit
- has_text_about_dose_unit
---

Predicate to describe the Text of DoseSchedule.

Use it like this: 
- [ #has_/text/_about_dose_unit :: Text ] or 
- [ has_text_about_dose_unit :: Text ] 

The unit of the dose, e.g. "mg".

Predicated describes that: 
[ #has_/domain  :: DoseSchedule ]
( #has_/name :: has_text_about_dose_unit )
( #has_/range :: Text )

