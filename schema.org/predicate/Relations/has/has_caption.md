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
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- caption
- caption
- caption
- has_caption
---

Use it like this: 
- [ #has/_caption :: MediaObject, Text] or 
- [ has_caption :: MediaObject, Text] 

The caption for this object. For downloadable machine formats (closed caption, subtitles etc.) use MediaObject and indicate the &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/encodingFormat&quot;&gt;encodingFormat&lt;/a&gt;.

Relation describes that: 
[ #has_/domain  :: AudioObject, ImageObject, VideoObject]
( #has_/name :: is_caption)
( #has_/range :: MediaObject, Text)

[ #has_/sub_properties :: embeddedTextCaption]

