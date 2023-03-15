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

title: has_early-prepayment-penalty
linkTitle: has_early-prepayment-penalty

keywords: [early-prepayment-penalty]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Quantity

aliases:
- early_prepayment_penalty
- early-prepayment-penalty
- earlyPrepaymentPenalty
- has_value_for_early_prepayment_penalty
---

Predicate to describe the Quantity of RepaymentSpecification.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/value/_for_early_prepayment_penalty :: MonetaryAmount ] or 
- [ has_value_for_early_prepayment_penalty :: MonetaryAmount ] 

The amount to be paid as a penalty in the event of early payment of the loan.

Predicate describes that: 
[ #has_/domain  :: RepaymentSpecification ]
( #has_/name :: has_value_for_early_prepayment_penalty )
( #has_/range :: MonetaryAmount )

