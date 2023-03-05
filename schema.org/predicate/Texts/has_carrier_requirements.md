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

title: has_text_about_carrier_requirements
linkTitle: has_text_about_carrier_requirements

keywords: [carrier, requirements]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- carrier-requirements
- carrier_requirements
- carrierRequirements
- has_text_about_carrier_requirements
---

Predicate to describe the Text of MobileApplication.

Use it like this: 
- [ #has_/text/_about_carrier_requirements :: Text ] or 
- [ has_text_about_carrier_requirements :: Text ] 

Specifies specific carrier(s) requirements for the application (e.g. an application may only work on a specific carrier network).

Predicated describes that: 
[ #has_/domain  :: MobileApplication ]
( #has_/name :: has_text_about_carrier_requirements )
( #has_/range :: Text )

