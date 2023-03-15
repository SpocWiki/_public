---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Url
publish: true

# Hugo Tags
type: Predi_Url

title: has_url_for_content_url
linkTitle: has_url_for_content_url

keywords: [content_url]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Url

aliases:
- content-url
- content_url
- contentUrl
- has_url_for_content_url
---

Predicate to specify the Url of MediaObject.

Use it like this: 
- [ #has_/url/_for_content_url :: URL ] or 
- [ has_url_for_content_url :: URL ] 

Actual bytes of the media object, for example the image file or video file.

Predicate describes that: 
[ #has_/domain  :: MediaObject ]
( #has_/name :: has_url_for_content_url )
( #has_/range :: URL )

