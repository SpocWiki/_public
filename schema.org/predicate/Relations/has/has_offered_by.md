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
title: has_offered_by

linkTitle: has_offered_by
keywords: [offered, by]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- offered-by
- offered_by
- offeredBy
- has_offered_by
---

Use it like this: 
- [ #has/_offered_by :: Organization, Person ] or 
- [ has_offered_by :: Organization, Person ] 

A pointer to the organization or person making the offer.

Relation describes that: 
[ #has_/domain  :: Offer ]
( #has_/name :: is_offered_by )
( #has_/range :: Organization, Person )

[ #is_/inverse_of  :: makesOffer ]

