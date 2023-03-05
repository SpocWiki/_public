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

title: has_text_about_file_size
linkTitle: has_text_about_file_size

keywords: [file, size]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- file-size
- file_size
- fileSize
- has_text_about_file_size
---

Predicate to describe the Text of SoftwareApplication.

Use it like this: 
- [ #has_/text/_about_file_size :: Text ] or 
- [ has_text_about_file_size :: Text ] 

Size of the application / package (e.g. 18MB). In the absence of a unit (MB, KB etc.), KB will be assumed.

Predicated describes that: 
[ #has_/domain  :: SoftwareApplication ]
( #has_/name :: has_text_about_file_size )
( #has_/range :: Text )

