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
keywords: [gender]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- gender
- gender
- gender
- has_gender
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_gender :: GenderType, Text ] or 
- [ has_gender :: GenderType, Text ] 

Gender of something, typically a &lt;a class="localLink" href="/Person"&gt;Person&lt;/a&gt;, but possibly also fictional characters, animals, etc. While Male and Female may be used, text strings are also acceptable for people who do not identify as a binary gender. The &lt;a class="localLink" href="/gender"&gt;gender&lt;/a&gt; property can also be used in an extended sense to cover e.g. the gender of sports teams. As with the gender of individuals, we do not try to enumerate all possibilities. A mixed-gender &lt;a class="localLink" href="/SportsTeam"&gt;SportsTeam&lt;/a&gt; can be indicated with a text value of "Mixed".

Relation describes that: 
[ #has_/domain  :: Person, SportsTeam ]
( #has_/name :: has_gender )
( #has_/range :: GenderType, Text )

