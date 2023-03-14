---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Relation
publish: true

# Hugo Tags
type: Predi_Relation
title: is_knowing_language

linkTitle: is_knowing_language
keywords: [knows, language]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- knows-language
- knows_language
- knowsLanguage
- is_knowing_language
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #is/_knowing_language :: Language, Text ] or 
- [ is_knowing_language :: Language, Text ] 

Of a &lt;a class="localLink" href="/Person"&gt;Person&lt;/a&gt;, and less typically of an &lt;a class="localLink" href="/Organization"&gt;Organization&lt;/a&gt;, to indicate a known language. We do not distinguish skill levels or reading/writing/speaking/signing here. Use language codes from the &lt;a href="http://tools.ietf.org/html/bcp47"&gt;IETF BCP 47 standard&lt;/a&gt;.

Relation describes that: 
[ #has_/domain  :: Organization, Person ]
( #has_/name :: is_knowing_language )
( #has_/range :: Language, Text )

