---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Boolean
publish: true

# Hugo Tags
type: Pred_Bool

title: is_live
linkTitle: is_live

keywords: [live]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/True

aliases:
- live-broadcast
- live
- isLiveBroadcast
- is_live
---

Use these simple Tags to mark Instances as True or False: 
#is_/_/live 
#is_/not/live 

Or write it as a Triple: 
[ is_live :: Boolean ] 

True if the broadcast is of a live event.

Predicate describes that: 
[ #has_/domain  :: BroadcastEvent ]
( #has_/name :: is_live )
( #has_/range :: Boolean )

