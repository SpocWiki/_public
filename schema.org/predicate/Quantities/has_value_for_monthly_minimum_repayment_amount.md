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

title: has_monthly-minimum-repayment-amount
linkTitle: has_monthly-minimum-repayment-amount

keywords: [monthly-minimum-repayment-amount]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/Quantity

aliases:
- monthly_minimum_repayment_amount
- monthly-minimum-repayment-amount
- monthlyMinimumRepaymentAmount
- has_value_for_monthly_minimum_repayment_amount
---

Predicate to describe the Quantity of PaymentCard.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/value/_for_monthly_minimum_repayment_amount :: MonetaryAmount, Number ] or 
- [ has_value_for_monthly_minimum_repayment_amount :: MonetaryAmount, Number ] 

The minimum payment is the lowest amount of money that one is required to pay on a credit card statement each month.

Predicate describes that: 
[ #has_/domain  :: PaymentCard ]
( #has_/name :: has_value_for_monthly_minimum_repayment_amount )
( #has_/range :: MonetaryAmount, Number )

