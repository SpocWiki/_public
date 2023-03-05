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

title: has_text_about_frequency
linkTitle: has_text_about_frequency

keywords: [frequency]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- frequency
- frequency
- frequency
- has_text_about_frequency
---

Predicate to describe the Text of DoseSchedule.

Use it like this: 
- [ #has_/text/_about_frequency :: Text ] or 
- [ has_text_about_frequency :: Text ] 

How often the dose is taken, e.g. "daily".

Predicated describes that: 
[ #has_/domain  :: DoseSchedule ]
( #has_/name :: is_frequency )
( #has_/range :: Text )

[ #has_/sub_properties :: [ repeatFrequency ] ]

