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

title: has_total-payment-due
linkTitle: has_total-payment-due

keywords: [total-payment-due]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Quantity

aliases:
- total_payment_due
- total-payment-due
- totalPaymentDue
- has_value_for_total_payment_due
---

Predicate to describe the Quantity of Invoice.

Use it like this: 
- [ #has_/value/_for_total_payment_due :: MonetaryAmount, PriceSpecification ] or 
- [ has_value_for_total_payment_due :: MonetaryAmount, PriceSpecification ] 

The total amount due.

Predicate describes that: 
[ #has_/domain  :: Invoice ]
( #has_/name :: has_value_for_total_payment_due )
( #has_/range :: MonetaryAmount, PriceSpecification )

