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

title: has_text_about_application_suite
linkTitle: has_text_about_application_suite

keywords: [application, suite]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- application-suite
- application_suite
- applicationSuite
- has_text_about_application_suite
---

Predicate to describe the Text of SoftwareApplication.

Use it like this: 
- [ #has_/text/_about_application_suite :: Text ] or 
- [ has_text_about_application_suite :: Text ] 

The name of the application suite to which the application belongs (e.g. Excel belongs to Office).

Predicated describes that: 
[ #has_/domain  :: SoftwareApplication ]
( #has_/name :: is_application_suite )
( #has_/range :: Text )

