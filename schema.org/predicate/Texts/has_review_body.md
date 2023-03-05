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

title: has_text_about_review_body
linkTitle: has_text_about_review_body

keywords: [review, body]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- review-body
- review_body
- reviewBody
- has_text_about_review_body
---

Predicate to describe the Text of Review.

Use it like this: 
- [ #has_/text/_about_review_body :: Text ] or 
- [ has_text_about_review_body :: Text ] 

The actual body of the review.

Predicated describes that: 
[ #has_/domain  :: Review ]
( #has_/name :: has_text_about_review_body )
( #has_/range :: Text )

