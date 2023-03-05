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
title: has_learning_resource_type

linkTitle: has_learning_resource_type
keywords: [learning, resource, type]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- learning-resource-type
- learning_resource_type
- learningResourceType
- has_learning_resource_type
---

Use it like this: 
- [ #has/_learning_resource_type :: DefinedTerm, Text ] or 
- [ has_learning_resource_type :: DefinedTerm, Text ] 

The predominant type or kind characterizing the learning resource. For example, &#x27;presentation&#x27;, &#x27;handout&#x27;.

Relation describes that: 
[ #has_/domain  :: CreativeWork, LearningResource ]
( #has_/name :: is_learning_resource_type )
( #has_/range :: DefinedTerm, Text )

