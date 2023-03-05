---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Text
publish: true

# Hugo Tags
type: Pred_Text

title: has_text_about_loan_type
linkTitle: has_text_about_loan_type

keywords: [loan, type]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- loan-type
- loan_type
- loanType
- has_text_about_loan_type
---

Predicate to describe the Text of LoanOrCredit.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_loan_type :: Text, URL ] or 
- [ has_text_about_loan_type :: Text, URL ] 

The type of a loan or credit.

Predicated describes that: 
[ #has_/domain  :: LoanOrCredit ]
( #has_/name :: is_loan_type )
( #has_/range :: Text, URL )

