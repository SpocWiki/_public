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

title: has_text_about_broadcast_timezone
linkTitle: has_text_about_broadcast_timezone

keywords: [broadcast, timezone]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- broadcast-timezone
- broadcast_timezone
- broadcastTimezone
- has_text_about_broadcast_timezone
---

Predicate to describe the Text of BroadcastService.

Use it like this: 
- [ #has_/text/_about_broadcast_timezone :: Text ] or 
- [ has_text_about_broadcast_timezone :: Text ] 

The timezone in &lt;a href="http://en.wikipedia.org/wiki/ISO_8601"&gt;ISO 8601 format&lt;/a&gt; for which the service bases its broadcasts.

Predicated describes that: 
[ #has_/domain  :: BroadcastService ]
( #has_/name :: has_text_about_broadcast_timezone )
( #has_/range :: Text )

