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

title: has_text_about_call_sign
linkTitle: has_text_about_call_sign

keywords: [call, sign]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- call-sign
- call_sign
- callSign
- has_text_about_call_sign
---

Predicate to describe the Text of BroadcastService, Person, Vehicle.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_call_sign :: Text ] or 
- [ has_text_about_call_sign :: Text ] 

A &lt;a href="https://en.wikipedia.org/wiki/Call_sign"&gt;callsign&lt;/a&gt;, as used in broadcasting and radio communications to identify people, radio and TV stations, or vehicles.

Predicated describes that: 
[ #has_/domain  :: BroadcastService, Person, Vehicle ]
( #has_/name :: has_text_about_call_sign )
( #has_/range :: Text )

[ #is_/sub_property_of  :: identifier ]

