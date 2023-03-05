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
title: has_knows_language

linkTitle: has_knows_language
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- knows-language
- knows_language
- knowsLanguage
- has_knows_language
---

[ #is_/part_of :: pending:]

Use it like this: 
- [ #has/_knows_language :: Language, Text] or 
- [ has_knows_language :: Language, Text] 

Of a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Person&quot;&gt;Person&lt;/a&gt;, and less typically of an &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Organization&quot;&gt;Organization&lt;/a&gt;, to indicate a known language. We do not distinguish skill levels or reading/writing/speaking/signing here. Use language codes from the &lt;a href&#x3D;&quot;http://tools.ietf.org/html/bcp47&quot;&gt;IETF BCP 47 standard&lt;/a&gt;.

Relation describes that: 
[ #has_/domain  :: Organization, Person]
( #has_/name :: is_knows_language)
( #has_/range :: Language, Text)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]
