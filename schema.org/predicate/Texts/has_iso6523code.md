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

title: has_text_about_iso6523code
linkTitle: has_text_about_iso6523code

keywords: [iso6523code]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- iso6523code
- iso6523code
- iso6523Code
- has_text_about_iso6523code
---

Predicate to describe the Text of Organization.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_iso6523code :: Text ] or 
- [ has_text_about_iso6523code :: Text ] 

An organization identifier as defined in ISO 6523(-1). Note that many existing organization identifiers such as &lt;a href&#x3D;&quot;leiCode&quot;&gt;leiCode&lt;/a&gt;, &lt;a href&#x3D;&quot;duns&quot;&gt;duns&lt;/a&gt; and &lt;a href&#x3D;&quot;vatID&quot;&gt;vatID&lt;/a&gt; can be expressed as an ISO 6523 identifier by setting the ICD part of the ISO 6523 identifier accordingly.

Predicated describes that: 
[ #has_/domain  :: Organization ]
( #has_/name :: has_text_about_iso6523code )
( #has_/range :: Text )

