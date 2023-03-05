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
title: is_in_language

linkTitle: is_in_language
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: language

tags:
- schema.org/Predicate/Relation

aliases:
- in-language
- in_language
- inLanguage
- is_in_language
---

Use it like this: 
- [ #is/_in_language :: Language, Text] or 
- [ is_in_language :: Language, Text] 

The language of the content or performance or used in an action. Please use one of the language codes from the &lt;a href&#x3D;&quot;http://tools.ietf.org/html/bcp47&quot;&gt;IETF BCP 47 standard&lt;/a&gt;. See also &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/availableLanguage&quot;&gt;availableLanguage&lt;/a&gt;.

Relation describes that: 
[ #has_/domain  :: BroadcastService, CommunicateAction, CreativeWork, Event, LinkRole, PronounceableText, WriteAction]
( #has_/name :: is_in_language)
( #has_/range :: Language, Text)

