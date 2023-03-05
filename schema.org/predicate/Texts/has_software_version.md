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

title: has_text_about_software_version
linkTitle: has_text_about_software_version

keywords: [software, version]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- software-version
- software_version
- softwareVersion
- has_text_about_software_version
---

Predicate to describe the Text of SoftwareApplication.

Use it like this: 
- [ #has_/text/_about_software_version :: Text ] or 
- [ has_text_about_software_version :: Text ] 

Version of the software instance.

Predicated describes that: 
[ #has_/domain  :: SoftwareApplication ]
( #has_/name :: has_text_about_software_version )
( #has_/range :: Text )

