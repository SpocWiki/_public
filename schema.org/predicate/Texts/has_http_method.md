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

title: has_text_about_http_method
linkTitle: has_text_about_http_method

keywords: [http, method]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- http-method
- http_method
- httpMethod
- has_text_about_http_method
---

Predicate to describe the Text of EntryPoint.

Use it like this: 
- [ #has_/text/_about_http_method :: Text ] or 
- [ has_text_about_http_method :: Text ] 

An HTTP method that specifies the appropriate HTTP method for a request to an HTTP EntryPoint. Values are capitalized strings as used in HTTP.

Predicated describes that: 
[ #has_/domain  :: EntryPoint ]
( #has_/name :: is_http_method )
( #has_/range :: Text )

