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

title: has_url_for_install_url
linkTitle: has_url_for_install_url

keywords: [install_url]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/Url

aliases:
- install-url
- install_url
- installUrl
- has_url_for_install_url
---

Predicate to specify the Url of SoftwareApplication.

Use it like this: 
- [ #has_/url/_for_install_url :: URL ] or 
- [ has_url_for_install_url :: URL ] 

URL at which the app may be installed, if different from the URL of the item.

Predicate describes that: 
[ #has_/domain  :: SoftwareApplication ]
( #has_/name :: has_url_for_install_url )
( #has_/range :: URL )

