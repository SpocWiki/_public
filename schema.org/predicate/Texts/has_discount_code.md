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

title: has_text_about_discount_code
linkTitle: has_text_about_discount_code

keywords: [discount, code]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- discount-code
- discount_code
- discountCode
- has_text_about_discount_code
---

Predicate to describe the Text of Order.

Use it like this: 
- [ #has_/text/_about_discount_code :: Text ] or 
- [ has_text_about_discount_code :: Text ] 

Code used to redeem a discount.

Predicated describes that: 
[ #has_/domain  :: Order ]
( #has_/name :: has_text_about_discount_code )
( #has_/range :: Text )

