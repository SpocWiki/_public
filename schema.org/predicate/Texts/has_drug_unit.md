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

title: has_text_about_drug_unit
linkTitle: has_text_about_drug_unit

keywords: [drug, unit]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- drug-unit
- drug_unit
- drugUnit
- has_text_about_drug_unit
---

Predicate to describe the Text of Drug, DrugCost.

Use it like this: 
- [ #has_/text/_about_drug_unit :: Text ] or 
- [ has_text_about_drug_unit :: Text ] 

The unit in which the drug is measured, e.g. "5 mg tablet".

Predicated describes that: 
[ #has_/domain  :: Drug, DrugCost ]
( #has_/name :: has_text_about_drug_unit )
( #has_/range :: Text )

