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

title: has_url_for_merchant_return_link
linkTitle: has_url_for_merchant_return_link

keywords: [merchant_return_link]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: productReturnLink

tags:
- schema.org/Predicate/Url

aliases:
- merchant-return-link
- merchant_return_link
- merchantReturnLink
- has_url_for_merchant_return_link
---

Predicate to specify the Url of MerchantReturnPolicy.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/url/_for_merchant_return_link :: URL ] or 
- [ has_url_for_merchant_return_link :: URL ] 

Specifies a Web page or service by URL, for product returns.

Predicate describes that: 
[ #has_/domain  :: MerchantReturnPolicy ]
( #has_/name :: has_url_for_merchant_return_link )
( #has_/range :: URL )

