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

title: has_occupancy
linkTitle: has_occupancy

keywords: [occupancy]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Quantity

aliases:
- occupancy
- occupancy
- occupancy
- has_value_for_occupancy
---

Predicate to describe the Quantity of Apartment, HotelRoom, SingleFamilyResidence, Suite.

Use it like this: 
- [ #has_/value/_for_occupancy :: QuantitativeValue ] or 
- [ has_value_for_occupancy :: QuantitativeValue ] 

The allowed total occupancy for the accommodation in persons (including infants etc). For individual accommodations, this is not necessarily the legal maximum but defines the permitted usage as per the contractual agreement (e.g. a double room used by a single person).
Typical unit code(s): C62 for person

Predicate describes that: 
[ #has_/domain  :: Apartment, HotelRoom, SingleFamilyResidence, Suite ]
( #has_/name :: has_value_for_occupancy )
( #has_/range :: QuantitativeValue )

