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

title: has_text_about_file_format
linkTitle: has_text_about_file_format

keywords: [file, format]
layout: 
draft: false
publishDate:
expiryDate: 

superseded_by: encodingFormat

tags:
- schema.org/Predicate/Text

aliases:
- file-format
- file_format
- fileFormat
- has_text_about_file_format
---

Predicate to describe the Text of CreativeWork.

Use it like this: 
- [ #has_/text/_about_file_format :: Text, URL ] or 
- [ has_text_about_file_format :: Text, URL ] 

Media type, typically MIME format (see &lt;a href&#x3D;&quot;http://www.iana.org/assignments/media-types/media-types.xhtml&quot;&gt;IANA site&lt;/a&gt;) of the content, e.g. application/zip of a SoftwareApplication binary. In cases where a CreativeWork has several media type representations, "encoding" can be used to indicate each MediaObject alongside particular fileFormat information. Unregistered or niche file formats can be indicated instead via the most appropriate URL, e.g. defining Web page or a Wikipedia entry.

Predicated describes that: 
[ #has_/domain  :: CreativeWork ]
( #has_/name :: is_file_format )
( #has_/range :: Text, URL )

