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

title: has_text_about_catalog_number
linkTitle: has_text_about_catalog_number

keywords: [catalog, number]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- catalog-number
- catalog_number
- catalogNumber
- has_text_about_catalog_number
---

Predicate to describe the Text of MusicRelease.

Use it like this: 
- [ #has_/text/_about_catalog_number :: Text ] or 
- [ has_text_about_catalog_number :: Text ] 

The catalog number for the release.

Predicated describes that: 
[ #has_/domain  :: MusicRelease ]
( #has_/name :: is_catalog_number )
( #has_/range :: Text )

