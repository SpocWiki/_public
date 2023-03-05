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

title: has_text_about_video_format
linkTitle: has_text_about_video_format

keywords: [video, format]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- video-format
- video_format
- videoFormat
- has_text_about_video_format
---

Predicate to describe the Text of BroadcastEvent, BroadcastService, ScreeningEvent.

Use it like this: 
- [ #has_/text/_about_video_format :: Text ] or 
- [ has_text_about_video_format :: Text ] 

The type of screening or video broadcast used (e.g. IMAX, 3D, SD, HD, etc.).

Predicated describes that: 
[ #has_/domain  :: BroadcastEvent, BroadcastService, ScreeningEvent ]
( #has_/name :: has_text_about_video_format )
( #has_/range :: Text )

