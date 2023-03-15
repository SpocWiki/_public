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

title: has_annual-percentage-rate
linkTitle: has_annual-percentage-rate

keywords: [annual-percentage-rate]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Quantity

aliases:
- annual_percentage_rate
- annual-percentage-rate
- annualPercentageRate
- has_value_for_annual_percentage_rate
---

Predicate to describe the Quantity of FinancialProduct.

Use it like this: 
- [ #has_/value/_for_annual_percentage_rate :: Number, QuantitativeValue ] or 
- [ has_value_for_annual_percentage_rate :: Number, QuantitativeValue ] 

The annual rate that is charged for borrowing (or made by investing), expressed as a single percentage number that represents the actual yearly cost of funds over the term of a loan. This includes any fees or additional costs associated with the transaction.

Predicate describes that: 
[ #has_/domain  :: FinancialProduct ]
( #has_/name :: has_value_for_annual_percentage_rate )
( #has_/range :: Number, QuantitativeValue )

