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

title: has_text_about_named_position
linkTitle: has_text_about_named_position

keywords: [named, position]
layout: 
draft: false
publishDate:
expiryDate: 

superseded_by: roleName

tags:
- schema.org/Predicate/Text

aliases:
- named-position
- named_position
- namedPosition
- has_text_about_named_position
---

Predicate to describe the Text of Role.

Use it like this: 
- [ #has_/text/_about_named_position :: Text, URL ] or 
- [ has_text_about_named_position :: Text, URL ] 

A position played, performed or filled by a person or organization, as part of an organization. For example, an athlete in a SportsTeam might play in the position named "Quarterback".

Predicated describes that: 
[ #has_/domain  :: Role ]
( #has_/name :: has_text_about_named_position )
( #has_/range :: Text, URL )

