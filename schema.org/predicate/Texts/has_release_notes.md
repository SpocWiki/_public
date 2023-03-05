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

title: has_text_about_release_notes
linkTitle: has_text_about_release_notes

keywords: [release, notes]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- release-notes
- release_notes
- releaseNotes
- has_text_about_release_notes
---

Predicate to describe the Text of SoftwareApplication.

Use it like this: 
- [ #has_/text/_about_release_notes :: Text, URL ] or 
- [ has_text_about_release_notes :: Text, URL ] 

Description of what changed in this version.

Predicated describes that: 
[ #has_/domain  :: SoftwareApplication ]
( #has_/name :: has_text_about_release_notes )
( #has_/range :: Text, URL )

