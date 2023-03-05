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
title: has_delivery_time

linkTitle: has_delivery_time
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
- delivery-time
- delivery_time
- deliveryTime
- has_delivery_time
---

[ #is_/part_of :: pending:]

Use it like this: 
- [ #has/_delivery_time :: ShippingDeliveryTime] or 
- [ has_delivery_time :: ShippingDeliveryTime] 

The total delay between the receipt of the order and the goods reaching the final customer.

Relation describes that: 
[ #has_/domain  :: DeliveryTimeSettings, OfferShippingDetails]
( #has_/name :: is_delivery_time)
( #has_/range :: ShippingDeliveryTime)

