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

title: has_text_about_tracking_number
linkTitle: has_text_about_tracking_number

keywords: [tracking, number]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- tracking-number
- tracking_number
- trackingNumber
- has_text_about_tracking_number
---

Predicate to describe the Text of ParcelDelivery.

Use it like this: 
- [ #has_/text/_about_tracking_number :: Text ] or 
- [ has_text_about_tracking_number :: Text ] 

Shipper tracking number.

Predicated describes that: 
[ #has_/domain  :: ParcelDelivery ]
( #has_/name :: is_tracking_number )
( #has_/range :: Text )

