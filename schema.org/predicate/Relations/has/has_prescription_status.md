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
title: has_prescription_status

linkTitle: has_prescription_status
keywords: [prescription, status]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- prescription-status
- prescription_status
- prescriptionStatus
- has_prescription_status
---

Use it like this: 
- [ #has/_prescription_status :: DrugPrescriptionStatus, Text ] or 
- [ has_prescription_status :: DrugPrescriptionStatus, Text ] 

Indicates the status of drug prescription, e.g. local catalogs classifications or whether the drug is available by prescription or over-the-counter, etc.

Relation describes that: 
[ #has_/domain  :: Drug ]
( #has_/name :: is_prescription_status )
( #has_/range :: DrugPrescriptionStatus, Text )

