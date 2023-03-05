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
title: has_payment_status

linkTitle: has_payment_status
keywords: [payment, status]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- payment-status
- payment_status
- paymentStatus
- has_payment_status
---

Use it like this: 
- [ #has/_payment_status :: PaymentStatusType, Text ] or 
- [ has_payment_status :: PaymentStatusType, Text ] 

The status of payment; whether the invoice has been paid or not.

Relation describes that: 
[ #has_/domain  :: Invoice ]
( #has_/name :: is_payment_status )
( #has_/range :: PaymentStatusType, Text )

