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

title: has_text_about_abstract
linkTitle: has_text_about_abstract

keywords: [abstract]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- abstract
- abstract
- abstract
- has_text_about_abstract
---

Predicate to describe the Text of CreativeWork.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_abstract :: Text ] or 
- [ has_text_about_abstract :: Text ] 

An abstract is a short description that summarizes a &lt;a class="localLink" href="/CreativeWork"&gt;CreativeWork&lt;/a&gt;.

Predicated describes that: 
[ #has_/domain  :: CreativeWork ]
( #has_/name :: has_text_about_abstract )
( #has_/range :: Text )

