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

title: has_geo_location_ineligible_region
linkTitle: has_geo_location_ineligible_region

keywords: [ineligible_region]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/geo

aliases:
- ineligible-region
- ineligible_region
- ineligibleRegion
- has_geo_location_ineligible_region
---

Predicate to describe the geo of ActionAccessSpecification, DeliveryChargeSpecification, Demand, MediaObject, Offer.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/geo/_ineligible_region :: GeoShape, Place, Text ] or 
- [ has_geo_ineligible_region :: GeoShape, Place, Text ] 

The ISO 3166-1 (ISO 3166-1 alpha-2) or ISO 3166-2 code, the place, or the GeoShape for the geo-political region(s) for which the offer or delivery charge specification is not valid, e.g. a region where the transaction is not allowed.&lt;br/&gt;&lt;br/&gt;

See also &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/eligibleRegion&quot;&gt;eligibleRegion&lt;/a&gt;.

Predicate describes that: 
[ #has_/domain  :: ActionAccessSpecification, DeliveryChargeSpecification, Demand, MediaObject, Offer ]
( #has_/name :: has_geo_location_ineligible_region )
( #has_/range :: GeoShape, Place, Text )

