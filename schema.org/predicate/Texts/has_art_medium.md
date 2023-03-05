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

title: has_text_about_art_medium
linkTitle: has_text_about_art_medium

keywords: [art, medium]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- art-medium
- art_medium
- artMedium
- has_text_about_art_medium
---

Predicate to describe the Text of VisualArtwork.

Use it like this: 
- [ #has_/text/_about_art_medium :: Text, URL ] or 
- [ has_text_about_art_medium :: Text, URL ] 

The material used. (E.g. Oil, Watercolour, Acrylic, Linoprint, Marble, Cyanotype, Digital, Lithograph, DryPoint, Intaglio, Pastel, Woodcut, Pencil, Mixed Media, etc.)

Predicated describes that: 
[ #has_/domain  :: VisualArtwork ]
( #has_/name :: is_art_medium )
( #has_/range :: Text, URL )

[ #is_/sub_property_of  :: material ]

