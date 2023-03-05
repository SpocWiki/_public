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

title: has_text_about_order_number
linkTitle: has_text_about_order_number

keywords: [order, number]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- order-number
- order_number
- orderNumber
- has_text_about_order_number
---

Predicate to describe the Text of Order.

Use it like this: 
- [ #has_/text/_about_order_number :: Text ] or 
- [ has_text_about_order_number :: Text ] 

The identifier of the transaction.

Predicated describes that: 
[ #has_/domain  :: Order ]
( #has_/name :: is_order_number )
( #has_/range :: Text )

[ #is_/sub_property_of  :: identifier ]

