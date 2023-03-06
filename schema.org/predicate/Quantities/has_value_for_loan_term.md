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

title: has_loan-term
linkTitle: has_loan-term

keywords: [loan-term]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Quantity

aliases:
- loan_term
- loan-term
- loanTerm
- has_value_for_loan_term
---

Predicate to describe the Quantity of LoanOrCredit.

Use it like this: 
- [ #has_/value/_for_loan_term :: QuantitativeValue ] or 
- [ has_value_for_loan_term :: QuantitativeValue ] 

The duration of the loan or credit agreement.

Predicate describes that: 
[ #has_/domain  :: LoanOrCredit ]
( #has_/name :: has_value_for_loan_term )
( #has_/range :: QuantitativeValue )

[ #is_/sub_property_of  :: duration ]

