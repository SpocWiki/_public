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
title: has_suggested_gender

linkTitle: has_suggested_gender
keywords: [suggested, gender]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- suggested-gender
- suggested_gender
- suggestedGender
- has_suggested_gender
---

Use it like this: 
- [ #has/_suggested_gender :: GenderType, Text ] or 
- [ has_suggested_gender :: GenderType, Text ] 

The suggested gender of the intended person or audience, for example &quot;male&quot;, &quot;female&quot;, or &quot;unisex&quot;.

Relation describes that: 
[ #has_/domain  :: PeopleAudience, SizeSpecification ]
( #has_/name :: is_suggested_gender )
( #has_/range :: GenderType, Text )

