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
title: is_complement_of

linkTitle: is_complement_of
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- complement-of
- complement_of
- is_complement_of
---

[ #is_/part_of :: https://meta.schema.org]

Use it like this: 
- [ #is_/complement_of :: Property] or 
- [ is_complement_of :: Property] 

Complementary Relations are typically Order Relations. 
They relate those pairs of items to each other, that the original Relation does NOT relate.

Don't confuse that with the [[is_inverse_of|inverse_of]] Relation where ARelatesB <=> BInverseA.

like [[is/is_lesser_than]] and [[is/is_greater_than]], where an Attribute of one Relation negates the Truth/Existence of the negated Relation. 

If a > b for a Relation,
then b > a is the Converse Relation 

Relation describes that: 
[ #has_/domain  :: Property]
( #has_/name :: is_complement_of)
( #has_/range :: Property)

