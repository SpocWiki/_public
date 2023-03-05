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
title: is_applying_to_delivery_method

linkTitle: is_applying_to_delivery_method
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
- applies-to-delivery-method
- applying_to_delivery_method
- appliesToDeliveryMethod
- is_applying_to_delivery_method
---

Use it like this: 
- [ #is/_applying_to_delivery_method :: DeliveryMethod] or 
- [ is_applying_to_delivery_method :: DeliveryMethod] 

The delivery method(s) to which the delivery charge or payment charge specification applies.

Relation describes that: 
[ #has_/domain  :: DeliveryChargeSpecification, PaymentChargeSpecification]
( #has_/name :: is_applying_to_delivery_method)
( #has_/range :: DeliveryMethod)

