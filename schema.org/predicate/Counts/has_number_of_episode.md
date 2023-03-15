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

title: has_number_of_episode_number
linkTitle: has_number_of_episode_number

keywords: [episode_number]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Count

aliases:
- episode-number
- episode_number
- episodeNumber
- has_number_of_episode
---

Predicate to describe the Number of Episode.

Use it like this: 
- [ #has_/number/_of_episode :: Integer, Text ] or 
- [ has_number_of_episode :: Integer, Text ] 

Position of the episode within an ordered group of episodes.

Predicate describes that: 
[ #has_/domain  :: Episode ]
( #has_/name :: has_number_of_episode )
( #has_/range :: Integer, Text )

[ #is_/sub_property_of  :: position ]

