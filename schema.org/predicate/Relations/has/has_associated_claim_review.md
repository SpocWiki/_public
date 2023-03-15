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

An associated [[ClaimReview]], related by specific common content, topic or claim. The expectation is that this property would be most typically used in cases where a single activity is conducting both claim reviews and media reviews, in which case [[relatedMediaReview]] would commonly be used on a [[ClaimReview]], while [[relatedClaimReview]] would be used on [[MediaReview]].

Relation describes that: 
[ #has_/domain  :: Review ]
( #has_/name :: has_associated_claim_review )
( #has_/range :: Review )

[ #is_/sub_property_of  :: associatedReview ]

