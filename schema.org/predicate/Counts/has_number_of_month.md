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

title: has_number_of_by_month_no
linkTitle: has_number_of_by_month_no

keywords: [by_month_no]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Count

aliases:
- by-month-no
- by_month_no
- byMonth
- has_number_of_month
---

Predicate to describe the Number of Schedule.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/number/_of_month :: Integer ] or 
- [ has_number_of_month :: Integer ] 

Defines the month(s) of the year on which a recurring <a class="localLink" href="/Event">Event</a> takes place. Specified as an <a class="localLink" href="/Integer">Integer</a> between 1-12. January is 1.

Predicate describes that: 
[ #has_/domain  :: Schedule ]
( #has_/name :: has_number_of_month )
( #has_/range :: Integer )

