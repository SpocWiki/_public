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

title: has_interest-rate
linkTitle: has_interest-rate

keywords: [interest-rate]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/Quantity

aliases:
- interest_rate
- interest-rate
- interestRate
- has_value_for_interest_rate
---

Predicate to describe the Quantity of FinancialProduct.

Use it like this: 
- [ #has_/value/_for_interest_rate :: Number, QuantitativeValue ] or 
- [ has_value_for_interest_rate :: Number, QuantitativeValue ] 

The interest rate, charged or paid, applicable to the financial product. Note: This is different from the calculated annualPercentageRate.

Predicate describes that: 
[ #has_/domain  :: FinancialProduct ]
( #has_/name :: has_value_for_interest_rate )
( #has_/range :: Number, QuantitativeValue )

