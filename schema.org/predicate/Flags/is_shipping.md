---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Boolean
publish: true

# Hugo Tags
type: Pred_Bool

title: is_shipping
linkTitle: is_shipping

keywords: [shipping]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/True

aliases:
- shipping
- shipping
- doesNotShip
- is_shipping
---

[ #is_/part_of :: pending: ]

Use these simple Tags to mark Instances as True or False: 
#is_/_/shipping 
#is_/not_/shipping 

Or write it as a Triple: 
[ is_shipping :: Boolean ] 

Indicates when shipping to a particular &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/shippingDestination&quot;&gt;shippingDestination&lt;/a&gt; is not available.

Predicate describes that: 
[ #has_/domain  :: OfferShippingDetails, ShippingRateSettings ]
( #has_/name :: is_shipping )
( #has_/range :: Boolean )

