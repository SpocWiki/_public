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
title: has_size_system

linkTitle: has_size_system
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
- size-system
- size_system
- sizeSystem
- has_size_system
---

[ #is_/part_of :: pending:]

Use it like this: 
- [ #has/_size_system :: SizeSystemEnumeration, Text] or 
- [ has_size_system :: SizeSystemEnumeration, Text] 

The size system used to identify a product&#x27;s size. Typically either a standard (for example, &quot;GS1&quot; or &quot;ISO-EN13402&quot;), country code (for example &quot;US&quot; or &quot;JP&quot;), or a measuring system (for example &quot;Metric&quot; or &quot;Imperial&quot;).

Relation describes that: 
[ #has_/domain  :: SizeSpecification]
( #has_/name :: is_size_system)
( #has_/range :: SizeSystemEnumeration, Text)

