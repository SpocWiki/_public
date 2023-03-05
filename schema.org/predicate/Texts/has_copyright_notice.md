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

title: has_text_about_copyright_notice
linkTitle: has_text_about_copyright_notice

keywords: [copyright, notice]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- copyright-notice
- copyright_notice
- copyrightNotice
- has_text_about_copyright_notice
---

Predicate to describe the Text of CreativeWork.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_copyright_notice :: Text ] or 
- [ has_text_about_copyright_notice :: Text ] 

Text of a notice appropriate for describing the copyright aspects of this Creative Work, ideally indicating the owner of the copyright for the Work.

Predicated describes that: 
[ #has_/domain  :: CreativeWork ]
( #has_/name :: has_text_about_copyright_notice )
( #has_/range :: Text )

