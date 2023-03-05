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

title: has_text_about_access_code
linkTitle: has_text_about_access_code

keywords: [access, code]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- access-code
- access_code
- accessCode
- has_text_about_access_code
---

Predicate to describe the Text of DeliveryEvent.

Use it like this: 
- [ #has_/text/_about_access_code :: Text ] or 
- [ has_text_about_access_code :: Text ] 

Password, PIN, or access code needed for delivery (e.g. from a locker).

Predicated describes that: 
[ #has_/domain  :: DeliveryEvent ]
( #has_/name :: has_text_about_access_code )
( #has_/range :: Text )

