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

title: has_url_for_download_url
linkTitle: has_url_for_download_url

keywords: [download_url]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Url

aliases:
- download-url
- download_url
- downloadUrl
- has_url_for_download_url
---

Predicate to specify the Url of SoftwareApplication.

Use it like this: 
- [ #has_/url/_for_download_url :: URL ] or 
- [ has_url_for_download_url :: URL ] 

If the file can be downloaded, URL to download the binary.

Predicate describes that: 
[ #has_/domain  :: SoftwareApplication ]
( #has_/name :: has_url_for_download_url )
( #has_/range :: URL )

