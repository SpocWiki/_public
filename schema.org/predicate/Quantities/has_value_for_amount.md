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

title: has_amount
linkTitle: has_amount

keywords: [amount]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Quantity

aliases:
- amount
- amount
- amount
- has_value_for_amount
---

Predicate to describe the Quantity of DatedMoneySpecification, InvestmentOrDeposit, LoanOrCredit, MonetaryGrant, MoneyTransfer.

Use it like this: 
- [ #has_/value/_for_amount :: MonetaryAmount, Number ] or 
- [ has_value_for_amount :: MonetaryAmount, Number ] 

The amount of money.

Predicate describes that: 
[ #has_/domain  :: DatedMoneySpecification, InvestmentOrDeposit, LoanOrCredit, MonetaryGrant, MoneyTransfer ]
( #has_/name :: has_value_for_amount )
( #has_/range :: MonetaryAmount, Number )

