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

title: has_text_about_sha256
linkTitle: has_text_about_sha256

keywords: [sha256]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- sha256
- sha256
- sha256
- has_text_about_sha256
---

Predicate to describe the Text of MediaObject.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_sha256 :: Text ] or 
- [ has_text_about_sha256 :: Text ] 

The &lt;a href&#x3D;&quot;https://en.wikipedia.org/wiki/SHA-2&quot;&gt;SHA-2&lt;/a&gt; SHA256 hash of the content of the item. For example, a zero-length input has value "e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855"

Predicated describes that: 
[ #has_/domain  :: MediaObject ]
( #has_/name :: has_text_about_sha256 )
( #has_/range :: Text )

[ #is_/sub_property_of  :: description ]

