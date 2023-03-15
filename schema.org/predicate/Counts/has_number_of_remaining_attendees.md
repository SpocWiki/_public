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

title: has_number_of_remaining_attendee_capacity
linkTitle: has_number_of_remaining_attendee_capacity

keywords: [remaining_attendee_capacity]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Count

aliases:
- remaining-attendee-capacity
- remaining_attendee_capacity
- remainingAttendeeCapacity
- has_number_of_remaining_attendees
---

Predicate to describe the Number of Event.

Use it like this: 
- [ #has_/number/_of_remaining_attendees :: Integer ] or 
- [ has_number_of_remaining_attendees :: Integer ] 

The number of attendee places for an event that remain unallocated.

Predicate describes that: 
[ #has_/domain  :: Event ]
( #has_/name :: has_number_of_remaining_attendees )
( #has_/range :: Integer )

