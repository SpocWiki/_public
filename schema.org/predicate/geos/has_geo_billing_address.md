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

title: has_geo_location_billing_address
linkTitle: has_geo_location_billing_address

keywords: [billing_address]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/geo

aliases:
- billing-address
- billing_address
- billingAddress
- has_geo_location_billing_address
---

Predicate to describe the geo of Order.

[ #is_/part_of ::  ]

Use it like this: 
- [ #has_/geo/_billing_address :: PostalAddress ] or 
- [ has_geo_billing_address :: PostalAddress ] 

The billing address for the order.

Predicate describes that: 
[ #has_/domain  :: Order ]
( #has_/name :: has_geo_location_billing_address )
( #has_/range :: PostalAddress )

[ #is_/inverse_of  ::  ]

[ #is_/sub_property_of  ::  ]

[ #has_/sub_properties :: [  ] ]

