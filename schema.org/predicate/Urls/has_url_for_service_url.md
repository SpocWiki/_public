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

title: has_url_for_service_url
linkTitle: has_url_for_service_url

keywords: [service_url]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/Url

aliases:
- service-url
- service_url
- serviceUrl
- has_url_for_service_url
---

Predicate to specify the Url of ServiceChannel.

Use it like this: 
- [ #has_/url/_for_service_url :: URL ] or 
- [ has_url_for_service_url :: URL ] 

The website to access the service.

Predicate describes that: 
[ #has_/domain  :: ServiceChannel ]
( #has_/name :: has_url_for_service_url )
( #has_/range :: URL )

