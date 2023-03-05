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

title: has_text_about_ingredients
linkTitle: has_text_about_ingredients

keywords: [ingredients]
layout: 
draft: false
publishDate:
expiryDate: 

superseded_by: recipeIngredient

tags:
- schema.org/Predicate/Text

aliases:
- ingredients
- ingredients
- ingredients
- has_text_about_ingredients
---

Predicate to describe the Text of Recipe.

Use it like this: 
- [ #has_/text/_about_ingredients :: Text ] or 
- [ has_text_about_ingredients :: Text ] 

A single ingredient used in the recipe, e.g. sugar, flour or garlic.

Predicated describes that: 
[ #has_/domain  :: Recipe ]
( #has_/name :: has_text_about_ingredients )
( #has_/range :: Text )

[ #is_/sub_property_of  :: supply ]

