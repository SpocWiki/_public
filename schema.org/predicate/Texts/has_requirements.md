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

title: has_text_about_requirements
linkTitle: has_text_about_requirements

keywords: [requirements]
layout: 
draft: false
publishDate:
expiryDate: 

superseded_by: softwareRequirements

tags:
- schema.org/Predicate/Text

aliases:
- requirements
- requirements
- requirements
- has_text_about_requirements
---

Predicate to describe the Text of SoftwareApplication.

Use it like this: 
- [ #has_/text/_about_requirements :: Text, URL ] or 
- [ has_text_about_requirements :: Text, URL ] 

Component dependency requirements for application. This includes runtime environments and shared libraries that are not included in the application distribution package, but required to run the application (examples: DirectX, Java or .NET runtime).

Predicated describes that: 
[ #has_/domain  :: SoftwareApplication ]
( #has_/name :: is_requirements )
( #has_/range :: Text, URL )

