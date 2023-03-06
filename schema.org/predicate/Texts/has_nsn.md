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

title: has_text_about_nsn
linkTitle: has_text_about_nsn

keywords: [nsn]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- nsn
- nsn
- nsn
- has_text_about_nsn
---

Predicate to describe the Text of Product.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_nsn :: Text ] or 
- [ has_text_about_nsn :: Text ] 

Indicates the &lt;a href="https://en.wikipedia.org/wiki/NATO_Stock_Number"&gt;NATO stock number&lt;/a&gt; (nsn) of a &lt;a class="localLink" href="/Product"&gt;Product&lt;/a&gt;.

Predicated describes that: 
[ #has_/domain  :: Product ]
( #has_/name :: has_text_about_nsn )
( #has_/range :: Text )

[ #is_/sub_property_of  :: identifier ]

