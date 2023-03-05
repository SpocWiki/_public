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
title: has_return_label_source

linkTitle: has_return_label_source
keywords: [return, label, source]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- return-label-source
- return_label_source
- returnLabelSource
- has_return_label_source
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_return_label_source :: ReturnLabelSourceEnumeration ] or 
- [ has_return_label_source :: ReturnLabelSourceEnumeration ] 

The method (from an enumeration) by which the customer obtains a return shipping label for a product returned for any reason.

Relation describes that: 
[ #has_/domain  :: MerchantReturnPolicy ]
( #has_/name :: is_return_label_source )
( #has_/range :: ReturnLabelSourceEnumeration )

