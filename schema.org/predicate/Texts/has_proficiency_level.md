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

title: has_text_about_proficiency_level
linkTitle: has_text_about_proficiency_level

keywords: [proficiency, level]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- proficiency-level
- proficiency_level
- proficiencyLevel
- has_text_about_proficiency_level
---

Predicate to describe the Text of TechArticle.

Use it like this: 
- [ #has_/text/_about_proficiency_level :: Text ] or 
- [ has_text_about_proficiency_level :: Text ] 

Proficiency needed for this content; expected values: "Beginner", "Expert".

Predicated describes that: 
[ #has_/domain  :: TechArticle ]
( #has_/name :: is_proficiency_level )
( #has_/range :: Text )

