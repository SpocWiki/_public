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

title: has_text_about_runtime_platform
linkTitle: has_text_about_runtime_platform

keywords: [runtime, platform]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: runtime

tags:
- schema.org/Predicate/Text

aliases:
- runtime-platform
- runtime_platform
- runtimePlatform
- has_text_about_runtime_platform
---

Predicate to describe the Text of SoftwareSourceCode.

Use it like this: 
- [ #has_/text/_about_runtime_platform :: Text ] or 
- [ has_text_about_runtime_platform :: Text ] 

Runtime platform or script interpreter dependencies (example: Java v1, Python 2.3, .NET Framework 3.0).

Predicated describes that: 
[ #has_/domain  :: SoftwareSourceCode ]
( #has_/name :: has_text_about_runtime_platform )
( #has_/range :: Text )

