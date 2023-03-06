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
title: has_associated_claim_review

linkTitle: has_associated_claim_review
keywords: [associated, claim, review]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- associated-claim-review
- associated_claim_review
- associatedClaimReview
- has_associated_claim_review
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_associated_claim_review :: Review ] or 
- [ has_associated_claim_review :: Review ] 

An associated &lt;a class="localLink" href="/ClaimReview"&gt;ClaimReview&lt;/a&gt;, related by specific common content, topic or claim. The expectation is that this property would be most typically used in cases where a single activity is conducting both claim reviews and media reviews, in which case &lt;a class="localLink" href="/relatedMediaReview"&gt;relatedMediaReview&lt;/a&gt; would commonly be used on a &lt;a class="localLink" href="/ClaimReview"&gt;ClaimReview&lt;/a&gt;, while &lt;a class="localLink" href="/relatedClaimReview"&gt;relatedClaimReview&lt;/a&gt; would be used on &lt;a class="localLink" href="/MediaReview"&gt;MediaReview&lt;/a&gt;.

Relation describes that: 
[ #has_/domain  :: Review ]
( #has_/name :: is_associated_claim_review )
( #has_/range :: Review )

[ #is_/sub_property_of  :: associatedReview ]

