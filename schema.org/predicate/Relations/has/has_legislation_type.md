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
title: has_legislation_type

linkTitle: has_legislation_type
keywords: [legislation, type]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- legislation-type
- legislation_type
- legislationType
- has_legislation_type
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_legislation_type :: CategoryCode, Text ] or 
- [ has_legislation_type :: CategoryCode, Text ] 

The type of the legislation. Examples of values are &quot;law&quot;, &quot;act&quot;, &quot;directive&quot;, &quot;decree&quot;, &quot;regulation&quot;, &quot;statutory instrument&quot;, &quot;loi organique&quot;, &quot;r�glement grand-ducal&quot;, etc., depending on the country.

Relation describes that: 
[ #has_/domain  :: Legislation ]
( #has_/name :: is_legislation_type )
( #has_/range :: CategoryCode, Text )

[ #is_/sub_property_of  :: genre ]

