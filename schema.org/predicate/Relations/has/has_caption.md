---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Relation
publish: true

# Hugo Tags
type: Predi_Relation
title: has_caption

linkTitle: has_caption
keywords: [caption]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- caption
- caption
- caption
- has_caption
---

Use it like this: 
- [ #has/_caption :: MediaObject, Text ] or 
- [ has_caption :: MediaObject, Text ] 

The caption for this object. For downloadable machine formats (closed caption, subtitles etc.) use MediaObject and indicate the [[encodingFormat]].

Relation describes that: 
[ #has_/domain  :: AudioObject, ImageObject, VideoObject ]
( #has_/name :: has_caption )
( #has_/range :: MediaObject, Text )

[ #has_/sub_properties :: [ embeddedTextCaption ] ]

