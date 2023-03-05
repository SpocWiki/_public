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
title: has_item_list_element

linkTitle: has_item_list_element
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
- item-list-element
- item_list_element
- itemListElement
- has_item_list_element
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_item_list_element :: ListItem, Text, Thing] or 
- [ has_item_list_element :: ListItem, Text, Thing] 

For itemListElement values, you can use simple strings (e.g. &quot;Peter&quot;, &quot;Paul&quot;, &quot;Mary&quot;), existing entities, or use ListItem.&lt;br/&gt;&lt;br/&gt;

Text values are best if the elements in the list are plain strings. Existing entities are best for a simple, unordered list of existing things in your data. ListItem is used with ordered lists when you want to provide additional context about the element in that list or when the same item might be in different places in different lists.&lt;br/&gt;&lt;br/&gt;

Note: The order of elements in your mark-up is not sufficient for indicating the order or elements.  Use ListItem with a &#x27;position&#x27; property in such cases.

Relation describes that: 
[ #has_/domain  :: ItemList]
( #has_/name :: is_item_list_element)
( #has_/range :: ListItem, Text, Thing)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]
