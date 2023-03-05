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

title: has_text_about_account_id
linkTitle: has_text_about_account_id

keywords: [account, id]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- account-id
- account_id
- accountId
- has_text_about_account_id
---

Predicate to describe the Text of Invoice.

Use it like this: 
- [ #has_/text/_about_account_id :: Text ] or 
- [ has_text_about_account_id :: Text ] 

The identifier for the account the payment will be applied to.

Predicated describes that: 
[ #has_/domain  :: Invoice ]
( #has_/name :: is_account_id )
( #has_/range :: Text )

[ #is_/sub_property_of  :: identifier ]

