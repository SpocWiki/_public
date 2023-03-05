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

title: has_text_about_variant_cover
linkTitle: has_text_about_variant_cover

keywords: [variant, cover]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- variant-cover
- variant_cover
- variantCover
- has_text_about_variant_cover
---

Predicate to describe the Text of ComicIssue.

[ #is_/part_of :: https://bib.schema.org ]

Use it like this: 
- [ #has_/text/_about_variant_cover :: Text ] or 
- [ has_text_about_variant_cover :: Text ] 

A description of the variant cover
        for the issue, if the issue is a variant printing. For example, &quot;Bryan Hitch
        Variant Cover&quot; or &quot;2nd Printing Variant&quot;.

Predicated describes that: 
[ #has_/domain  :: ComicIssue ]
( #has_/name :: is_variant_cover )
( #has_/range :: Text )

