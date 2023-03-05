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
title: has_interaction_type

linkTitle: has_interaction_type
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
- interaction-type
- interaction_type
- interactionType
- has_interaction_type
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_interaction_type :: Action] or 
- [ has_interaction_type :: Action] 

The Action representing the type of interaction. For up votes, +1s, etc. use &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/LikeAction&quot;&gt;LikeAction&lt;/a&gt;. For down votes use &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/DislikeAction&quot;&gt;DislikeAction&lt;/a&gt;. Otherwise, use the most specific Action.

Relation describes that: 
[ #has_/domain  :: InteractionCounter]
( #has_/name :: is_interaction_type)
( #has_/range :: Action)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]

