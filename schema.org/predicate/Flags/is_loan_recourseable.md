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

title: is_loan_recourseable
linkTitle: is_loan_recourseable

keywords: [loan_recourseable]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/True

aliases:
- recourse-loan
- loan_recourseable
- recourseLoan
- is_loan_recourseable
---

[ #is_/part_of :: pending: ]

Use these simple Tags to mark Instances as True or False: 
#is_/_/loan_recourseable 
#is_/not_/loan_recourseable 

Or write it as a Triple: 
[ is_loan_recourseable :: Boolean ] 

The only way you get the money back in the event of default is the security. Recourse is where you still have the opportunity to go back to the borrower for the rest of the money.

Predicate describes that: 
[ #has_/domain  :: LoanOrCredit ]
( #has_/name :: is_loan_recourseable )
( #has_/range :: Boolean )

