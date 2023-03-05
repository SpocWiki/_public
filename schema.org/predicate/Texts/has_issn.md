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

title: has_text_about_issn
linkTitle: has_text_about_issn

keywords: [issn]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- issn
- issn
- issn
- has_text_about_issn
---

Predicate to describe the Text of Blog, CreativeWorkSeries, Dataset, WebSite.

Use it like this: 
- [ #has_/text/_about_issn :: Text ] or 
- [ has_text_about_issn :: Text ] 

The International Standard Serial Number (ISSN) that identifies this serial publication. You can repeat this property to identify different formats of, or the linking ISSN (ISSN-L) for, this serial publication.

Predicated describes that: 
[ #has_/domain  :: Blog, CreativeWorkSeries, Dataset, WebSite ]
( #has_/name :: has_text_about_issn )
( #has_/range :: Text )

[ #is_/sub_property_of  :: identifier ]

