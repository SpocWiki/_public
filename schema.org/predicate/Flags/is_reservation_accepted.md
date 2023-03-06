---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Boolean
publish: true

# Hugo Tags
type: Pred_Bool

title: is_reservation_accepted
linkTitle: is_reservation_accepted

keywords: [reservation_accepted]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/True

aliases:
- reservation-accepted
- reservation_accepted
- acceptsReservations
- is_reservation_accepted
---

Use these simple Tags to mark Instances as True or False: 
#is_/_/reservation_accepted 
#is_/not/reservation_accepted 

Or write it as a Triple: 
[ is_reservation_accepted :: Boolean, Text, URL ] 

Indicates whether a FoodEstablishment accepts reservations. Values can be Boolean, an URL at which reservations can be made or (for backwards compatibility) the strings &lt;code&gt;Yes&lt;/code&gt; or &lt;code&gt;No&lt;/code&gt;.

Predicate describes that: 
[ #has_/domain  :: FoodEstablishment ]
( #has_/name :: is_reservation_accepted )
( #has_/range :: Boolean, Text, URL )

