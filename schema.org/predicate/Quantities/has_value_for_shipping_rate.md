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

title: has_shipping-rate
linkTitle: has_shipping-rate

keywords: [shipping-rate]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Quantity

aliases:
- shipping_rate
- shipping-rate
- shippingRate
- has_value_for_shipping_rate
---

Predicate to describe the Quantity of OfferShippingDetails, ShippingRateSettings.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/value/_for_shipping_rate :: MonetaryAmount ] or 
- [ has_value_for_shipping_rate :: MonetaryAmount ] 

The shipping rate is the cost of shipping to the specified destination. Typically, the maxValue and currency values (of the &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/MonetaryAmount&quot;&gt;MonetaryAmount&lt;/a&gt;) are most appropriate.

Predicate describes that: 
[ #has_/domain  :: OfferShippingDetails, ShippingRateSettings ]
( #has_/name :: has_value_for_shipping_rate )
( #has_/range :: MonetaryAmount )

