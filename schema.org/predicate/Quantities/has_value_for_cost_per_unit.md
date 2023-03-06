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

title: has_cost-per-unit
linkTitle: has_cost-per-unit

keywords: [cost-per-unit]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/Quantity

aliases:
- cost_per_unit
- cost-per-unit
- costPerUnit
- has_value_for_cost_per_unit
---

Predicate to describe the Quantity of DrugCost.

Use it like this: 
- [ #has_/value/_for_cost_per_unit :: Number, QualitativeValue, Text ] or 
- [ has_value_for_cost_per_unit :: Number, QualitativeValue, Text ] 

The cost per unit of the drug.

Predicate describes that: 
[ #has_/domain  :: DrugCost ]
( #has_/name :: has_value_for_cost_per_unit )
( #has_/range :: Number, QualitativeValue, Text )

