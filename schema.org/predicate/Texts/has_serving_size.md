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

title: has_text_about_serving_size
linkTitle: has_text_about_serving_size

keywords: [serving, size]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- serving-size
- serving_size
- servingSize
- has_text_about_serving_size
---

Predicate to describe the Text of NutritionInformation.

Use it like this: 
- [ #has_/text/_about_serving_size :: Text ] or 
- [ has_text_about_serving_size :: Text ] 

The serving size, in terms of the number of volume or mass.

Predicated describes that: 
[ #has_/domain  :: NutritionInformation ]
( #has_/name :: is_serving_size )
( #has_/range :: Text )

