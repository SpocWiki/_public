---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Relation
publish: true

# Hugo Tags
type: Predi_Relation
title: is_applying_to_payment_method

linkTitle: is_applying_to_payment_method
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- applies-to-payment-method
- applying_to_payment_method
- appliesToPaymentMethod
- is_applying_to_payment_method
---

Use it like this: 
- [ #is/_applying_to_payment_method :: PaymentMethod] or 
- [ is_applying_to_payment_method :: PaymentMethod] 

The payment method(s) to which the payment charge specification applies.

Relation describes that: 
[ #has_/domain  :: PaymentChargeSpecification]
( #has_/name :: is_applying_to_payment_method)
( #has_/range :: PaymentMethod)

