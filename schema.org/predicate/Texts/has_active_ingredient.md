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

title: has_text_about_active_ingredient
linkTitle: has_text_about_active_ingredient

keywords: [active, ingredient]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- active-ingredient
- active_ingredient
- activeIngredient
- has_text_about_active_ingredient
---

Predicate to describe the Text of DietarySupplement, Drug, DrugStrength, Substance.

Use it like this: 
- [ #has_/text/_about_active_ingredient :: Text ] or 
- [ has_text_about_active_ingredient :: Text ] 

An active ingredient, typically chemical compounds and/or biologic substances.

Predicated describes that: 
[ #has_/domain  :: DietarySupplement, Drug, DrugStrength, Substance ]
( #has_/name :: is_active_ingredient )
( #has_/range :: Text )

