---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Quantity
publish: true

# Hugo Tags
type: Predi_Quantity

title: has_recipe-yield
linkTitle: has_recipe-yield

keywords: [recipe-yield]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/Quantity

aliases:
- recipe_yield
- recipe-yield
- recipeYield
- has_value_for_is_yielding_servings
---

Predicate to describe the Quantity of Recipe.

Use it like this: 
- [ #has_/value/_for_is_yielding_servings :: QuantitativeValue, Text ] or 
- [ has_value_for_is_yielding_servings :: QuantitativeValue, Text ] 

The quantity produced by the recipe (for example, number of people served, number of servings, etc).

Predicate describes that: 
[ #has_/domain  :: Recipe ]
( #has_/name :: has_value_for_is_yielding_servings )
( #has_/range :: QuantitativeValue, Text )

[ #is_/sub_property_of  :: yield ]

