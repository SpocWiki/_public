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

title: has_url_for_payment_url
linkTitle: has_url_for_payment_url

keywords: [payment_url]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/Url

aliases:
- payment-url
- payment_url
- paymentUrl
- has_url_for_payment_url
---

Predicate to specify the Url of Order.

Use it like this: 
- [ #has_/url/_for_payment_url :: URL ] or 
- [ has_url_for_payment_url :: URL ] 

The URL for sending a payment.

Predicate describes that: 
[ #has_/domain  :: Order ]
( #has_/name :: has_url_for_payment_url )
( #has_/range :: URL )

