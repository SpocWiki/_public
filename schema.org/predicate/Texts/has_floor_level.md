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

title: has_text_about_floor_level
linkTitle: has_text_about_floor_level

keywords: [floor, level]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- floor-level
- floor_level
- floorLevel
- has_text_about_floor_level
---

Predicate to describe the Text of Accommodation.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_floor_level :: Text ] or 
- [ has_text_about_floor_level :: Text ] 

The floor level for an &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Accommodation&quot;&gt;Accommodation&lt;/a&gt; in a multi-storey building. Since counting
  systems &lt;a href&#x3D;&quot;https://en.wikipedia.org/wiki/Storey#Consecutive_number_floor_designations&quot;&gt;vary internationally&lt;/a&gt;, the local system should be used where possible.

Predicated describes that: 
[ #has_/domain  :: Accommodation ]
( #has_/name :: has_text_about_floor_level )
( #has_/range :: Text )

