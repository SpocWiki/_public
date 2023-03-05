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

title: has_text_about_required_collateral
linkTitle: has_text_about_required_collateral

keywords: [required, collateral]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- required-collateral
- required_collateral
- requiredCollateral
- has_text_about_required_collateral
---

Predicate to describe the Text of LoanOrCredit.

Use it like this: 
- [ #has_/text/_about_required_collateral :: Text, Thing ] or 
- [ has_text_about_required_collateral :: Text, Thing ] 

Assets required to secure loan or credit repayments. It may take form of third party pledge, goods, financial instruments (cash, securities, etc.)

Predicated describes that: 
[ #has_/domain  :: LoanOrCredit ]
( #has_/name :: has_text_about_required_collateral )
( #has_/range :: Text, Thing )

