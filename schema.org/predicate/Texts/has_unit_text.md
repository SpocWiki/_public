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

title: has_text_about_unit_text
linkTitle: has_text_about_unit_text

keywords: [unit, text]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- unit-text
- unit_text
- unitText
- has_text_about_unit_text
---

Predicate to describe the Text of PropertyValue, QuantitativeValue, TypeAndQuantityNode, UnitPriceSpecification.

Use it like this: 
- [ #has_/text/_about_unit_text :: Text ] or 
- [ has_text_about_unit_text :: Text ] 

A string or text indicating the unit of measurement. Useful if you cannot provide a standard unit code for
&lt;a href="unitCode"&gt;unitCode&lt;/a&gt;.

Predicated describes that: 
[ #has_/domain  :: PropertyValue, QuantitativeValue, TypeAndQuantityNode, UnitPriceSpecification ]
( #has_/name :: has_text_about_unit_text )
( #has_/range :: Text )

