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

title: has_url_for_reply_to_url
linkTitle: has_url_for_reply_to_url

keywords: [reply_to_url]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Url

aliases:
- reply-to-url
- reply_to_url
- replyToUrl
- has_url_for_reply_to_url
---

Predicate to specify the Url of UserComments.

Use it like this: 
- [ #has_/url/_for_reply_to_url :: URL ] or 
- [ has_url_for_reply_to_url :: URL ] 

The URL at which a reply may be posted to the specified UserComment.

Predicate describes that: 
[ #has_/domain  :: UserComments ]
( #has_/name :: has_url_for_reply_to_url )
( #has_/range :: URL )

