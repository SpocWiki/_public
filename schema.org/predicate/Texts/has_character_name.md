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

title: has_text_about_character_name
linkTitle: has_text_about_character_name

keywords: [character, name]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- character-name
- character_name
- characterName
- has_text_about_character_name
---

Predicate to describe the Text of PerformanceRole.

Use it like this: 
- [ #has_/text/_about_character_name :: Text ] or 
- [ has_text_about_character_name :: Text ] 

The name of a character played in some acting or performing role, i.e. in a PerformanceRole.

Predicated describes that: 
[ #has_/domain  :: PerformanceRole ]
( #has_/name :: has_text_about_character_name )
( #has_/range :: Text )

