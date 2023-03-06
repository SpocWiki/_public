---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Quantity
publish: true

# Hugo Tags
type: Predi_Quantity

title: has_down-payment
linkTitle: has_down-payment

keywords: [down-payment]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Quantity

aliases:
- down_payment
- down-payment
- downPayment
- has_value_for_down_payment
---

Predicate to describe the Quantity of RepaymentSpecification.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/value/_for_down_payment :: MonetaryAmount, Number ] or 
- [ has_value_for_down_payment :: MonetaryAmount, Number ] 

a type of payment made in cash during the onset of the purchase of an expensive good/service. The payment typically represents only a percentage of the full purchase price.

Predicate describes that: 
[ #has_/domain  :: RepaymentSpecification ]
( #has_/name :: has_value_for_down_payment )
( #has_/range :: MonetaryAmount, Number )

