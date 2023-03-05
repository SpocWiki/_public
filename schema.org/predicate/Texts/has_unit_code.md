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

title: has_text_about_unit_code
linkTitle: has_text_about_unit_code

keywords: [unit, code]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- unit-code
- unit_code
- unitCode
- has_text_about_unit_code
---

Predicate to describe the Text of PropertyValue, QuantitativeValue, TypeAndQuantityNode, UnitPriceSpecification.

Use it like this: 
- [ #has_/text/_about_unit_code :: Text, URL ] or 
- [ has_text_about_unit_code :: Text, URL ] 

The unit of measurement given using the UN/CEFACT Common Code (3 characters) or a URL. Other codes than the UN/CEFACT Common Code may be used with a prefix followed by a colon.

Predicated describes that: 
[ #has_/domain  :: PropertyValue, QuantitativeValue, TypeAndQuantityNode, UnitPriceSpecification ]
( #has_/name :: is_unit_code )
( #has_/range :: Text, URL )

