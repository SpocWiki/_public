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
title: has_layout_image

linkTitle: has_layout_image
keywords: [layout, image]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- layout-image
- layout_image
- layoutImage
- has_layout_image
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_layout_image :: ImageObject, URL ] or 
- [ has_layout_image :: ImageObject, URL ] 

A schematic image showing the floorplan layout.

Relation describes that: 
[ #has_/domain  :: FloorPlan ]
( #has_/name :: has_layout_image )
( #has_/range :: ImageObject, URL )

[ #is_/sub_property_of  :: image ]

