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

title: has_number_of_position
linkTitle: has_number_of_position

keywords: [position]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Count

aliases:
- position
- position
- position
- has_number_of_position
---

Predicate to describe the Number of CreativeWork, ListItem.

Use it like this: 
- [ #has_/number/_of_position :: Integer, Text ] or 
- [ has_number_of_position :: Integer, Text ] 

The position of an item in a series or sequence of items.

Predicate describes that: 
[ #has_/domain  :: CreativeWork, ListItem ]
( #has_/name :: has_number_of_position )
( #has_/range :: Integer, Text )

[ #has_/sub_properties :: [ clipNumber, episodeNumber, issueNumber, seasonNumber, volumeNumber ] ]

