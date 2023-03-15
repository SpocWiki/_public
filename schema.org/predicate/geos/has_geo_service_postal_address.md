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

title: has_geo_location_service_postal_address
linkTitle: has_geo_location_service_postal_address

keywords: [service_postal_address]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/geo

aliases:
- service-postal-address
- service_postal_address
- servicePostalAddress
- has_geo_location_service_postal_address
---

Predicate to describe the geo of ServiceChannel.

Use it like this: 
- [ #has_/geo/_service_postal_address :: PostalAddress ] or 
- [ has_geo_service_postal_address :: PostalAddress ] 

The address for accessing the service by mail.

Predicate describes that: 
[ #has_/domain  :: ServiceChannel ]
( #has_/name :: has_geo_location_service_postal_address )
( #has_/range :: PostalAddress )

