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

title: has_text_about_icao_code
linkTitle: has_text_about_icao_code

keywords: [icao, code]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- icao-code
- icao_code
- icaoCode
- has_text_about_icao_code
---

Predicate to describe the Text of Airport.

Use it like this: 
- [ #has_/text/_about_icao_code :: Text ] or 
- [ has_text_about_icao_code :: Text ] 

ICAO identifier for an airport.

Predicated describes that: 
[ #has_/domain  :: Airport ]
( #has_/name :: has_text_about_icao_code )
( #has_/range :: Text )

