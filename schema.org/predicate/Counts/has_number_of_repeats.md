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

title: has_number_of_repeat_count
linkTitle: has_number_of_repeat_count

keywords: [repeat_count]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Count

aliases:
- repeat-count
- repeat_count
- repeatCount
- has_number_of_repeats
---

Predicate to describe the Number of Schedule.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/number/_of_repeats :: Integer ] or 
- [ has_number_of_repeats :: Integer ] 

Defines the number of times a recurring <a class="localLink" href="/Event">Event</a> will take place.

Predicate describes that: 
[ #has_/domain  :: Schedule ]
( #has_/name :: has_number_of_repeats )
( #has_/range :: Integer )

