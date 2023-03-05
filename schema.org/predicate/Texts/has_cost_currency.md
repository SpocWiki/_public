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

title: has_text_about_cost_currency
linkTitle: has_text_about_cost_currency

keywords: [cost, currency]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- cost-currency
- cost_currency
- costCurrency
- has_text_about_cost_currency
---

Predicate to describe the Text of DrugCost.

Use it like this: 
- [ #has_/text/_about_cost_currency :: Text ] or 
- [ has_text_about_cost_currency :: Text ] 

The currency (in 3-letter) of the drug cost. See: http://en.wikipedia.org/wiki/ISO_4217.

Predicated describes that: 
[ #has_/domain  :: DrugCost ]
( #has_/name :: has_text_about_cost_currency )
( #has_/range :: Text )

