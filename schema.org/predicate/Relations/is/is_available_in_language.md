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
title: is_available_in_language

linkTitle: is_available_in_language
keywords: [available, language]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- available-language
- available_language
- availableLanguage
- is_available_in_language
---

Use it like this: 
- [ #has/_available_language :: Language, Text ] or 
- [ is_available_in_language :: Language, Text ] 

A language someone may use with or at the item, service or place. Please use one of the language codes from the &lt;a href="http://tools.ietf.org/html/bcp47"&gt;IETF BCP 47 standard&lt;/a&gt;. See also &lt;a class="localLink" href="/inLanguage"&gt;inLanguage&lt;/a&gt;.

Relation describes that: 
[ #has_/domain  :: ContactPoint, LodgingBusiness, ServiceChannel, TouristAttraction ]
( #has_/name :: is_available_in_language )
( #has_/range :: [[../../../Type/is_a_thing/intangible/language]], Text )

