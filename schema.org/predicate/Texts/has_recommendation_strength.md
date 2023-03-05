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

title: has_text_about_recommendation_strength
linkTitle: has_text_about_recommendation_strength

keywords: [recommendation, strength]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- recommendation-strength
- recommendation_strength
- recommendationStrength
- has_text_about_recommendation_strength
---

Predicate to describe the Text of MedicalGuidelineRecommendation.

Use it like this: 
- [ #has_/text/_about_recommendation_strength :: Text ] or 
- [ has_text_about_recommendation_strength :: Text ] 

Strength of the guideline"s recommendation (e.g. "class I").

Predicated describes that: 
[ #has_/domain  :: MedicalGuidelineRecommendation ]
( #has_/name :: is_recommendation_strength )
( #has_/range :: Text )

