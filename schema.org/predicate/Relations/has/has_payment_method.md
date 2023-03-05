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
title: has_payment_method

linkTitle: has_payment_method
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- payment-method
- payment_method
- paymentMethod
- has_payment_method
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_payment_method :: PaymentMethod] or 
- [ has_payment_method :: PaymentMethod] 

The name of the credit card or other method of payment for the order.

Relation describes that: 
[ #has_/domain  :: Invoice, Order]
( #has_/name :: is_payment_method)
( #has_/range :: PaymentMethod)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]

