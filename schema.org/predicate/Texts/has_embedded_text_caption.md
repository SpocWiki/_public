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

title: has_text_about_embedded_text_caption
linkTitle: has_text_about_embedded_text_caption

keywords: [embedded, text, caption]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- embedded-text-caption
- embedded_text_caption
- embeddedTextCaption
- has_text_about_embedded_text_caption
---

Predicate to describe the Text of AudioObject, ImageObject, VideoObject.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_embedded_text_caption :: Text ] or 
- [ has_text_about_embedded_text_caption :: Text ] 

Represents textual captioning from a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/MediaObject&quot;&gt;MediaObject&lt;/a&gt;, e.g. text of a "meme".

Predicated describes that: 
[ #has_/domain  :: AudioObject, ImageObject, VideoObject ]
( #has_/name :: has_text_about_embedded_text_caption )
( #has_/range :: Text )

[ #is_/sub_property_of  :: caption ]

