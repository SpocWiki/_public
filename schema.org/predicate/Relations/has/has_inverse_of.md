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
title: has_inverse_of

linkTitle: has_inverse_of
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
- inverse-of
- inverse_of
- inverseOf
- has_inverse_of
---

[ #is_/part_of :: https://meta.schema.org]

Use it like this: 
- [ #has/_inverse_of :: Property] or 
- [ has_inverse_of :: Property] 

Relates a property to a property that is its inverse. Inverse properties relate the same pairs of items to each other, but in reversed direction. For example, the &#x27;alumni&#x27; and &#x27;alumniOf&#x27; properties are inverseOf each other. Some properties don&#x27;t have explicit inverses; in these situations RDFa and JSON-LD syntax for reverse properties can be used.

Relation describes that: 
[ #has_/domain  :: Property]
( #has_/name :: is_inverse_of)
( #has_/range :: Property)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]

