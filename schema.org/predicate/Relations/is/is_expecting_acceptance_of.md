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
title: is_expecting_acceptance_of

linkTitle: is_expecting_acceptance_of
keywords: [expects, acceptance, of]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- expects-acceptance-of
- expects_acceptance_of
- expectsAcceptanceOf
- is_expecting_acceptance_of
---

Use it like this: 
- [ #is/_expecting_acceptance_of :: Offer ] or 
- [ is_expecting_acceptance_of :: Offer ] 

An Offer which must be accepted before the user can perform the Action. For example, the user may need to buy a movie before being able to watch it.

Relation describes that: 
[ #has_/domain  :: ActionAccessSpecification, ConsumeAction, MediaSubscription ]
( #has_/name :: is_expects_acceptance_of )
( #has_/range :: Offer )

