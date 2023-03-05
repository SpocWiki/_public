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

title: has_text_about_broadcast_display_name
linkTitle: has_text_about_broadcast_display_name

keywords: [broadcast, display, name]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- broadcast-display-name
- broadcast_display_name
- broadcastDisplayName
- has_text_about_broadcast_display_name
---

Predicate to describe the Text of BroadcastService.

Use it like this: 
- [ #has_/text/_about_broadcast_display_name :: Text ] or 
- [ has_text_about_broadcast_display_name :: Text ] 

The name displayed in the channel guide. For many US affiliates, it is the network name.

Predicated describes that: 
[ #has_/domain  :: BroadcastService ]
( #has_/name :: has_text_about_broadcast_display_name )
( #has_/range :: Text )

