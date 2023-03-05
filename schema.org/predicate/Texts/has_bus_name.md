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

title: has_text_about_bus_name
linkTitle: has_text_about_bus_name

keywords: [bus, name]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- bus-name
- bus_name
- busName
- has_text_about_bus_name
---

Predicate to describe the Text of BusTrip.

Use it like this: 
- [ #has_/text/_about_bus_name :: Text ] or 
- [ has_text_about_bus_name :: Text ] 

The name of the bus (e.g. Bolt Express).

Predicated describes that: 
[ #has_/domain  :: BusTrip ]
( #has_/name :: is_bus_name )
( #has_/range :: Text )

