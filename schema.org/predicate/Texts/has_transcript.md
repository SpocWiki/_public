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

title: has_text_about_transcript
linkTitle: has_text_about_transcript

keywords: [transcript]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- transcript
- transcript
- transcript
- has_text_about_transcript
---

Predicate to describe the Text of AudioObject, VideoObject.

Use it like this: 
- [ #has_/text/_about_transcript :: Text ] or 
- [ has_text_about_transcript :: Text ] 

If this MediaObject is an AudioObject or VideoObject, the transcript of that object.

Predicated describes that: 
[ #has_/domain  :: AudioObject, VideoObject ]
( #has_/name :: has_text_about_transcript )
( #has_/range :: Text )

