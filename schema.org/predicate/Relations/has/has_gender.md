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
title: has_gender

linkTitle: has_gender
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
- gender
- gender
- gender
- has_gender
---

[ #is_/part_of :: pending:]

Use it like this: 
- [ #has/_gender :: GenderType, Text] or 
- [ has_gender :: GenderType, Text] 

Gender of something, typically a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Person&quot;&gt;Person&lt;/a&gt;, but possibly also fictional characters, animals, etc. While Male and Female may be used, text strings are also acceptable for people who do not identify as a binary gender. The &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/gender&quot;&gt;gender&lt;/a&gt; property can also be used in an extended sense to cover e.g. the gender of sports teams. As with the gender of individuals, we do not try to enumerate all possibilities. A mixed-gender &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/SportsTeam&quot;&gt;SportsTeam&lt;/a&gt; can be indicated with a text value of &quot;Mixed&quot;.

Relation describes that: 
[ #has_/domain  :: Person, SportsTeam]
( #has_/name :: is_gender)
( #has_/range :: GenderType, Text)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]
