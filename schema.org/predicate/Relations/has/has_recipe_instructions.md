---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Relation
publish: true

# Hugo Tags
type: Predi_Relation
title: has_recipe_instructions

linkTitle: has_recipe_instructions
keywords: [recipe, instructions]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- recipe-instructions
- recipe_instructions
- recipeInstructions
- has_recipe_instructions
---

Use it like this: 
- [ #has/_recipe_instructions :: CreativeWork, ItemList, Text ] or 
- [ has_recipe_instructions :: CreativeWork, ItemList, Text ] 

A step in making the recipe, in the form of a single item (document, video, etc.) or an ordered list with HowToStep and/or HowToSection items.

Relation describes that: 
[ #has_/domain  :: Recipe ]
( #has_/name :: is_recipe_instructions )
( #has_/range :: CreativeWork, ItemList, Text )

[ #is_/sub_property_of  :: step ]

