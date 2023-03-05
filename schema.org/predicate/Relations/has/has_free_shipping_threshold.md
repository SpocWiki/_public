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
title: has_free_shipping_threshold

linkTitle: has_free_shipping_threshold
keywords: [free, shipping, threshold]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- free-shipping-threshold
- free_shipping_threshold
- freeShippingThreshold
- has_free_shipping_threshold
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_free_shipping_threshold :: DeliveryChargeSpecification, MonetaryAmount ] or 
- [ has_free_shipping_threshold :: DeliveryChargeSpecification, MonetaryAmount ] 

A monetary value above (or at) which the shipping rate becomes free. Intended to be used via an &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/OfferShippingDetails&quot;&gt;OfferShippingDetails&lt;/a&gt; with &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/shippingSettingsLink&quot;&gt;shippingSettingsLink&lt;/a&gt; matching this &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/ShippingRateSettings&quot;&gt;ShippingRateSettings&lt;/a&gt;.

Relation describes that: 
[ #has_/domain  :: ShippingRateSettings ]
( #has_/name :: is_free_shipping_threshold )
( #has_/range :: DeliveryChargeSpecification, MonetaryAmount )

