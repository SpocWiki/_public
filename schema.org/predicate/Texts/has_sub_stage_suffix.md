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

title: has_text_about_sub_stage_suffix
linkTitle: has_text_about_sub_stage_suffix

keywords: [sub, stage, suffix]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- sub-stage-suffix
- sub_stage_suffix
- subStageSuffix
- has_text_about_sub_stage_suffix
---

Predicate to describe the Text of MedicalConditionStage.

Use it like this: 
- [ #has_/text/_about_sub_stage_suffix :: Text ] or 
- [ has_text_about_sub_stage_suffix :: Text ] 

The substage, e.g. "a" for Stage IIIa.

Predicated describes that: 
[ #has_/domain  :: MedicalConditionStage ]
( #has_/name :: has_text_about_sub_stage_suffix )
( #has_/range :: Text )

