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
title: has_delivery_status

linkTitle: has_delivery_status
keywords: [delivery, status]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- delivery-status
- delivery_status
- deliveryStatus
- has_delivery_status
---

Use it like this: 
- [ #has/_delivery_status :: DeliveryEvent ] or 
- [ has_delivery_status :: DeliveryEvent ] 

New entry added as the package passes through each leg of its journey (from shipment to final delivery).

Relation describes that: 
[ #has_/domain  :: ParcelDelivery ]
( #has_/name :: has_delivery_status )
( #has_/range :: DeliveryEvent )

