---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Boolean
publish: true

# Hugo Tags
type: Pred_Bool

title: is_mortgage_domiciled
linkTitle: is_mortgage_domiciled

keywords: [mortgage_domiciled]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/True

aliases:
- domiciled-mortgage
- mortgage_domiciled
- domiciledMortgage
- is_mortgage_domiciled
---

[ #is_/part_of :: pending: ]

Use these simple Tags to mark Instances as True or False: 
#is_/_/mortgage_domiciled 
#is_/not_/mortgage_domiciled 

Or write it as a Triple: 
[ is_mortgage_domiciled :: Boolean ] 

Whether borrower is a resident of the jurisdiction where the property is located.

Predicate describes that: 
[ #has_/domain  :: MortgageLoan ]
( #has_/name :: is_mortgage_domiciled )
( #has_/range :: Boolean )

