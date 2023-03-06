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

title: has_geo_location_delivery_address
linkTitle: has_geo_location_delivery_address

keywords: [delivery_address]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/geo

aliases:
- delivery-address
- delivery_address
- deliveryAddress
- has_geo_location_delivery_address
---

Predicate to describe the geo of ParcelDelivery.

[ #is_/part_of ::  ]

Use it like this: 
- [ #has_/geo/_delivery_address :: PostalAddress ] or 
- [ has_geo_delivery_address :: PostalAddress ] 

Destination address.

Predicate describes that: 
[ #has_/domain  :: ParcelDelivery ]
( #has_/name :: has_geo_location_delivery_address )
( #has_/range :: PostalAddress )

[ #is_/inverse_of  ::  ]

[ #is_/sub_property_of  ::  ]

[ #has_/sub_properties :: [  ] ]

