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

title: has_delivery-lead-time
linkTitle: has_delivery-lead-time

keywords: [delivery-lead-time]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/Quantity

aliases:
- delivery_lead_time
- delivery-lead-time
- deliveryLeadTime
- has_value_for_delivery_lead_time
---

Predicate to describe the Quantity of Demand, Offer.

Use it like this: 
- [ #has_/value/_for_delivery_lead_time :: QuantitativeValue ] or 
- [ has_value_for_delivery_lead_time :: QuantitativeValue ] 

The typical delay between the receipt of the order and the goods either leaving the warehouse or being prepared for pickup, in case the delivery method is on site pickup.

Predicate describes that: 
[ #has_/domain  :: Demand, Offer ]
( #has_/name :: has_value_for_delivery_lead_time )
( #has_/range :: QuantitativeValue )

