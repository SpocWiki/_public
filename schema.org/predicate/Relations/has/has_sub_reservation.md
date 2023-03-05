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
title: has_sub_reservation

linkTitle: has_sub_reservation
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- sub-reservation
- sub_reservation
- subReservation
- has_sub_reservation
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_sub_reservation :: Reservation] or 
- [ has_sub_reservation :: Reservation] 

The individual reservations included in the package. Typically a repeated property.

Relation describes that: 
[ #has_/domain  :: ReservationPackage]
( #has_/name :: is_sub_reservation)
( #has_/range :: Reservation)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]
