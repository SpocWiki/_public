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

title: has_number_of_by_month_day
linkTitle: has_number_of_by_month_day

keywords: [by_month_day]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/Count

aliases:
- by-month-day
- by_month_day
- byMonthDay
- has_number_of_day_in_month
---

Predicate to describe the Number of Schedule.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/number/_of_day_in_month :: Integer ] or 
- [ has_number_of_day_in_month :: Integer ] 

Defines the day(s) of the month on which a recurring <a class="localLink" href="/Event">Event</a> takes place. Specified as an <a class="localLink" href="/Integer">Integer</a> between 1-31.

Predicate describes that: 
[ #has_/domain  :: Schedule ]
( #has_/name :: has_number_of_day_in_month )
( #has_/range :: Integer )

