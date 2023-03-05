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

title: has_text_about_browser_requirements
linkTitle: has_text_about_browser_requirements

keywords: [browser, requirements]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- browser-requirements
- browser_requirements
- browserRequirements
- has_text_about_browser_requirements
---

Predicate to describe the Text of WebApplication.

Use it like this: 
- [ #has_/text/_about_browser_requirements :: Text ] or 
- [ has_text_about_browser_requirements :: Text ] 

Specifies browser requirements in human-readable text. For example, "requires HTML5 support".

Predicated describes that: 
[ #has_/domain  :: WebApplication ]
( #has_/name :: has_text_about_browser_requirements )
( #has_/range :: Text )

