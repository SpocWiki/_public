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
title: has_refund_type

linkTitle: has_refund_type
keywords: [refund, type]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- refund-type
- refund_type
- refundType
- has_refund_type
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_refund_type :: RefundTypeEnumeration ] or 
- [ has_refund_type :: RefundTypeEnumeration ] 

A refund type, from an enumerated list.

Relation describes that: 
[ #has_/domain  :: MerchantReturnPolicy ]
( #has_/name :: is_refund_type )
( #has_/range :: RefundTypeEnumeration )

