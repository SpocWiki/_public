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

title: has_text_about_available_on_device
linkTitle: has_text_about_available_on_device

keywords: [available, on, device]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: device

tags:
- schema.org/Predicate/Text

aliases:
- available-on-device
- available_on_device
- availableOnDevice
- has_text_about_available_on_device
---

Predicate to describe the Text of SoftwareApplication.

Use it like this: 
- [ #has_/text/_about_available_on_device :: Text ] or 
- [ has_text_about_available_on_device :: Text ] 

Device required to run the application. Used in cases where a specific make/model is required to run the application.

Predicated describes that: 
[ #has_/domain  :: SoftwareApplication ]
( #has_/name :: has_text_about_available_on_device )
( #has_/range :: Text )

