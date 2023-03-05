---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Text
publish: true

# Hugo Tags
type: Pred_Text

title: has_text_about_passenger_sequence_number
linkTitle: has_text_about_passenger_sequence_number

keywords: [passenger, sequence, number]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- passenger-sequence-number
- passenger_sequence_number
- passengerSequenceNumber
- has_text_about_passenger_sequence_number
---

Predicate to describe the Text of FlightReservation.

Use it like this: 
- [ #has_/text/_about_passenger_sequence_number :: Text ] or 
- [ has_text_about_passenger_sequence_number :: Text ] 

The passenger"s sequence number as assigned by the airline.

Predicated describes that: 
[ #has_/domain  :: FlightReservation ]
( #has_/name :: has_text_about_passenger_sequence_number )
( #has_/range :: Text )

