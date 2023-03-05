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
- delivery-status
- delivery_status
- deliveryStatus
- has_delivery_status
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_delivery_status :: DeliveryEvent] or 
- [ has_delivery_status :: DeliveryEvent] 

New entry added as the package passes through each leg of its journey (from shipment to final delivery).

Relation describes that: 
[ #has_/domain  :: ParcelDelivery]
( #has_/name :: is_delivery_status)
( #has_/range :: DeliveryEvent)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]

