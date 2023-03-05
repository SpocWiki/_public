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
title: has_beneficiary_bank

linkTitle: has_beneficiary_bank
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
- beneficiary-bank
- beneficiary_bank
- beneficiaryBank
- has_beneficiary_bank
---

[ #is_/part_of :: pending:]

Use it like this: 
- [ #has/_beneficiary_bank :: BankOrCreditUnion, Text] or 
- [ has_beneficiary_bank :: BankOrCreditUnion, Text] 

A bank or bank�s branch, financial institution or international financial institution operating the beneficiary�s bank account or releasing funds for the beneficiary.

Relation describes that: 
[ #has_/domain  :: MoneyTransfer]
( #has_/name :: is_beneficiary_bank)
( #has_/range :: BankOrCreditUnion, Text)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]
