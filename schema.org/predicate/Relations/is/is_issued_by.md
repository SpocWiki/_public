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
title: is_issued_by

linkTitle: is_issued_by
keywords: [issued, by]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- issued-by
- issued_by
- issuedBy
- is_issued_by
---

Use it like this: 
- [ #is/_issued_by :: Organization ] or 
- [ is_issued_by :: Organization ] 

The organization issuing the ticket or permit.

Relation describes that: 
[ #has_/domain  :: Permit, Ticket ]
( #has_/name :: is_issued_by )
( #has_/range :: Organization )

