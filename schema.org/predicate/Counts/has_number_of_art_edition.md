---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Count
publish: true

# Hugo Tags
type: Predi_Count

title: has_number_of_art_edition
linkTitle: has_number_of_art_edition

keywords: [art_edition]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/Count

aliases:
- art-edition
- art_edition
- artEdition
- has_number_of_art_edition
---

Predicate to describe the Number of VisualArtwork.

Use it like this: 
- [ #has_/number/_of_art_edition :: Integer, Text ] or 
- [ has_number_of_art_edition :: Integer, Text ] 

The number of copies when multiple copies of a piece of artwork are produced - e.g. for a limited edition of 20 prints, 'artEdition' refers to the total number of copies (in this example "20").

Predicate describes that: 
[ #has_/domain  :: VisualArtwork ]
( #has_/name :: has_number_of_art_edition )
( #has_/range :: Integer, Text )

