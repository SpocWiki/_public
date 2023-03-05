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

title: has_text_about_alignment_type
linkTitle: has_text_about_alignment_type

keywords: [alignment, type]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- alignment-type
- alignment_type
- alignmentType
- has_text_about_alignment_type
---

Predicate to describe the Text of AlignmentObject.

Use it like this: 
- [ #has_/text/_about_alignment_type :: Text ] or 
- [ has_text_about_alignment_type :: Text ] 

A category of alignment between the learning resource and the framework node. Recommended values include: "requires", "textComplexity", "readingLevel", and "educationalSubject".

Predicated describes that: 
[ #has_/domain  :: AlignmentObject ]
( #has_/name :: has_text_about_alignment_type )
( #has_/range :: Text )

