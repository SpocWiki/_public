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

title: has_url_for_tracking_url
linkTitle: has_url_for_tracking_url

keywords: [tracking_url]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Url

aliases:
- tracking-url
- tracking_url
- trackingUrl
- has_url_for_tracking_url
---

Predicate to specify the Url of ParcelDelivery.

Use it like this: 
- [ #has_/url/_for_tracking_url :: URL ] or 
- [ has_url_for_tracking_url :: URL ] 

Tracking url for the parcel delivery.

Predicate describes that: 
[ #has_/domain  :: ParcelDelivery ]
( #has_/name :: has_url_for_tracking_url )
( #has_/range :: URL )

