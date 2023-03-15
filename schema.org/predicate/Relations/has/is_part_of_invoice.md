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
title: is_part_of_invoice

linkTitle: is_part_of_invoice
keywords: [part, of, invoice]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- part-of-invoice
- part_of_invoice
- partOfInvoice
- is_part_of_invoice
---

Use it like this: 
- [ #is/_part_of_invoice :: Invoice ] or 
- [ is_part_of_invoice :: Invoice ] 

The order is being paid as part of the referenced Invoice.

Relation describes that: 
[ #has_/domain  :: Order ]
( #has_/name :: is_part_of_invoice )
( #has_/range :: Invoice )

