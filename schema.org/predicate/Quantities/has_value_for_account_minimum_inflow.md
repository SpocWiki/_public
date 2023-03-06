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

title: has_account-minimum-inflow
linkTitle: has_account-minimum-inflow

keywords: [account-minimum-inflow]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/Quantity

aliases:
- account_minimum_inflow
- account-minimum-inflow
- accountMinimumInflow
- has_value_for_account_minimum_inflow
---

Predicate to describe the Quantity of BankAccount.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/value/_for_account_minimum_inflow :: MonetaryAmount ] or 
- [ has_value_for_account_minimum_inflow :: MonetaryAmount ] 

A minimum amount that has to be paid in every month.

Predicate describes that: 
[ #has_/domain  :: BankAccount ]
( #has_/name :: has_value_for_account_minimum_inflow )
( #has_/range :: MonetaryAmount )

