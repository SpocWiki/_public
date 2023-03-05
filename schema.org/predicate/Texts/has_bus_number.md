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

title: has_text_about_bus_number
linkTitle: has_text_about_bus_number

keywords: [bus, number]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- bus-number
- bus_number
- busNumber
- has_text_about_bus_number
---

Predicate to describe the Text of BusTrip.

Use it like this: 
- [ #has_/text/_about_bus_number :: Text ] or 
- [ has_text_about_bus_number :: Text ] 

The unique identifier for the bus.

Predicated describes that: 
[ #has_/domain  :: BusTrip ]
( #has_/name :: has_text_about_bus_number )
( #has_/range :: Text )

