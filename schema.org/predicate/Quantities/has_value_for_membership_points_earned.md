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

title: has_membership-points-earned
linkTitle: has_membership-points-earned

keywords: [membership-points-earned]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Quantity

aliases:
- membership_points_earned
- membership-points-earned
- membershipPointsEarned
- has_value_for_membership_points_earned
---

Predicate to describe the Quantity of ProgramMembership.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/value/_for_membership_points_earned :: Number, QuantitativeValue ] or 
- [ has_value_for_membership_points_earned :: Number, QuantitativeValue ] 

The number of membership points earned by the member. If necessary, the unitText can be used to express the units the points are issued in. (E.g. stars, miles, etc.)

Predicate describes that: 
[ #has_/domain  :: ProgramMembership ]
( #has_/name :: has_value_for_membership_points_earned )
( #has_/range :: Number, QuantitativeValue )

