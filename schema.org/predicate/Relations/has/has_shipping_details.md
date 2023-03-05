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
title: has_shipping_details

linkTitle: has_shipping_details
keywords: [shipping, details]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- shipping-details
- shipping_details
- shippingDetails
- has_shipping_details
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_shipping_details :: OfferShippingDetails ] or 
- [ has_shipping_details :: OfferShippingDetails ] 

Indicates information about the shipping policies and options associated with an &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Offer&quot;&gt;Offer&lt;/a&gt;.

Relation describes that: 
[ #has_/domain  :: Offer ]
( #has_/name :: is_shipping_details )
( #has_/range :: OfferShippingDetails )

