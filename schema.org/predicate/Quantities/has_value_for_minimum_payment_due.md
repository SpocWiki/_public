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

title: has_minimum-payment-due
linkTitle: has_minimum-payment-due

keywords: [minimum-payment-due]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Quantity

aliases:
- minimum_payment_due
- minimum-payment-due
- minimumPaymentDue
- has_value_for_minimum_payment_due
---

Predicate to describe the Quantity of Invoice.

Use it like this: 
- [ #has_/value/_for_minimum_payment_due :: MonetaryAmount, PriceSpecification ] or 
- [ has_value_for_minimum_payment_due :: MonetaryAmount, PriceSpecification ] 

The minimum payment required at this time.

Predicate describes that: 
[ #has_/domain  :: Invoice ]
( #has_/name :: has_value_for_minimum_payment_due )
( #has_/range :: MonetaryAmount, PriceSpecification )

