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

title: has_text_about_confirmation_number
linkTitle: has_text_about_confirmation_number

keywords: [confirmation, number]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- confirmation-number
- confirmation_number
- confirmationNumber
- has_text_about_confirmation_number
---

Predicate to describe the Text of Invoice, Order.

Use it like this: 
- [ #has_/text/_about_confirmation_number :: Text ] or 
- [ has_text_about_confirmation_number :: Text ] 

A number that confirms the given order or payment has been received.

Predicated describes that: 
[ #has_/domain  :: Invoice, Order ]
( #has_/name :: has_text_about_confirmation_number )
( #has_/range :: Text )

[ #is_/sub_property_of  :: identifier ]

