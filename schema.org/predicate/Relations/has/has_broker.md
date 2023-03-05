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
title: has_broker

linkTitle: has_broker
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: bookingAgent
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- broker
- broker
- broker
- has_broker
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_broker :: Organization, Person] or 
- [ has_broker :: Organization, Person] 

An entity that arranges for an exchange between a buyer and a seller.  In most cases a broker never acquires or releases ownership of a product or service involved in an exchange.  If it is not clear whether an entity is a broker, seller, or buyer, the latter two terms are preferred.

Relation describes that: 
[ #has_/domain  :: Invoice, Order, Reservation, Service]
( #has_/name :: is_broker)
( #has_/range :: Organization, Person)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]
