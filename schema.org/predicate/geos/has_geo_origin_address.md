---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate geo
publish: true

# Hugo Tags
type: Pred_geo

title: has_geo_location_origin_address
linkTitle: has_geo_location_origin_address

keywords: [origin_address]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/geo

aliases:
- origin-address
- origin_address
- originAddress
- has_geo_location_origin_address
---

Predicate to describe the geo of ParcelDelivery.

Use it like this: 
- [ #has_/geo/_origin_address :: PostalAddress ] or 
- [ has_geo_origin_address :: PostalAddress ] 

Shipper&#x27;s address.

Predicate describes that: 
[ #has_/domain  :: ParcelDelivery ]
( #has_/name :: has_geo_location_origin_address )
( #has_/range :: PostalAddress )

