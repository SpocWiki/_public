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

title: has_net-worth
linkTitle: has_net-worth

keywords: [net-worth]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Quantity

aliases:
- net_worth
- net-worth
- netWorth
- has_value_for_net_worth
---

Predicate to describe the Quantity of Person.

Use it like this: 
- [ #has_/value/_for_net_worth :: MonetaryAmount, PriceSpecification ] or 
- [ has_value_for_net_worth :: MonetaryAmount, PriceSpecification ] 

The total financial value of the person as calculated by subtracting assets from liabilities.

Predicate describes that: 
[ #has_/domain  :: Person ]
( #has_/name :: has_value_for_net_worth )
( #has_/range :: MonetaryAmount, PriceSpecification )

