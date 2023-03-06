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

title: has_text_about_rating_explanation
linkTitle: has_text_about_rating_explanation

keywords: [rating, explanation]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- rating-explanation
- rating_explanation
- ratingExplanation
- has_text_about_rating_explanation
---

Predicate to describe the Text of Rating.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_rating_explanation :: Text ] or 
- [ has_text_about_rating_explanation :: Text ] 

A short explanation (e.g. one to two sentences) providing background context and other information that led to the conclusion expressed in the rating. This is particularly applicable to ratings associated with "fact check" markup using &lt;a class="localLink" href="/ClaimReview"&gt;ClaimReview&lt;/a&gt;.

Predicated describes that: 
[ #has_/domain  :: Rating ]
( #has_/name :: has_text_about_rating_explanation )
( #has_/range :: Text )

