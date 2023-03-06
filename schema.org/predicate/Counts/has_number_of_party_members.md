---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Count
publish: true

# Hugo Tags
type: Predi_Count

title: has_number_of_party_size
linkTitle: has_number_of_party_size

keywords: [party_size]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/Count

aliases:
- party-size
- party_size
- partySize
- has_number_of_party_members
---

Predicate to describe the Number of FoodEstablishmentReservation, TaxiReservation.

Use it like this: 
- [ #has_/number/_of_party_members :: Integer, QuantitativeValue ] or 
- [ has_number_of_party_members :: Integer, QuantitativeValue ] 

Number of people the reservation should accommodate.

Predicate describes that: 
[ #has_/domain  :: FoodEstablishmentReservation, TaxiReservation ]
( #has_/name :: has_number_of_party_members )
( #has_/range :: Integer, QuantitativeValue )

