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

title: has_text_about_recipe_ingredient
linkTitle: has_text_about_recipe_ingredient

keywords: [recipe, ingredient]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: ingredients

tags:
- schema.org/Predicate/Text

aliases:
- recipe-ingredient
- recipe_ingredient
- recipeIngredient
- has_text_about_recipe_ingredient
---

Predicate to describe the Text of Recipe.

Use it like this: 
- [ #has_/text/_about_recipe_ingredient :: Text ] or 
- [ has_text_about_recipe_ingredient :: Text ] 

A single ingredient used in the recipe, e.g. sugar, flour or garlic.

Predicated describes that: 
[ #has_/domain  :: Recipe ]
( #has_/name :: is_recipe_ingredient )
( #has_/range :: Text )

[ #is_/sub_property_of  :: supply ]

