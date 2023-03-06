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

title: has_review-rating
linkTitle: has_review-rating

keywords: [review-rating]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/Quantity

aliases:
- review_rating
- review-rating
- reviewRating
- has_value_for_review_rating_stars
---

Predicate to describe the Quantity of Review.

Use it like this: 
- [ #has_/value/_for_review_rating_stars :: Rating ] or 
- [ has_value_for_review_rating_stars :: Rating ] 

The rating given in this review. Note that reviews can themselves be rated. The &lt;code&gt;reviewRating&lt;/code&gt; applies to rating given by the review. The &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/aggregateRating&quot;&gt;aggregateRating&lt;/a&gt; property applies to the review itself, as a creative work.

Predicate describes that: 
[ #has_/domain  :: Review ]
( #has_/name :: has_value_for_review_rating_stars )
( #has_/range :: Rating )

