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

title: has_url_for_embed_url
linkTitle: has_url_for_embed_url

keywords: [embed_url]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Url

aliases:
- embed-url
- embed_url
- embedUrl
- has_url_for_embed_url
---

Predicate to specify the Url of MediaObject.

Use it like this: 
- [ #has_/url/_for_embed_url :: URL ] or 
- [ has_url_for_embed_url :: URL ] 

A URL pointing to a player for a specific video. In general, this is the information in the &lt;code&gt;src&lt;/code&gt; element of an &lt;code&gt;embed&lt;/code&gt; tag and should not be the same as the content of the &lt;code&gt;loc&lt;/code&gt; tag.

Predicate describes that: 
[ #has_/domain  :: MediaObject ]
( #has_/name :: has_url_for_embed_url )
( #has_/range :: URL )

