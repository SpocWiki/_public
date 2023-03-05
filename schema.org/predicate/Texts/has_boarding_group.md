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

title: has_text_about_boarding_group
linkTitle: has_text_about_boarding_group

keywords: [boarding, group]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- boarding-group
- boarding_group
- boardingGroup
- has_text_about_boarding_group
---

Predicate to describe the Text of FlightReservation.

Use it like this: 
- [ #has_/text/_about_boarding_group :: Text ] or 
- [ has_text_about_boarding_group :: Text ] 

The airline-specific indicator of boarding order / preference.

Predicated describes that: 
[ #has_/domain  :: FlightReservation ]
( #has_/name :: has_text_about_boarding_group )
( #has_/range :: Text )

