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

title: has_text_about_cost_origin
linkTitle: has_text_about_cost_origin

keywords: [cost, origin]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- cost-origin
- cost_origin
- costOrigin
- has_text_about_cost_origin
---

Predicate to describe the Text of DrugCost.

Use it like this: 
- [ #has_/text/_about_cost_origin :: Text ] or 
- [ has_text_about_cost_origin :: Text ] 

Additional details to capture the origin of the cost data. For example, "Medicare Part B".

Predicated describes that: 
[ #has_/domain  :: DrugCost ]
( #has_/name :: is_cost_origin )
( #has_/range :: Text )

