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
title: is_using_device

linkTitle: is_using_device
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
- uses-device
- using_device
- usesDevice
- is_using_device
---

Use it like this: 
- [ #is/_using_device :: MedicalDevice] or 
- [ is_using_device :: MedicalDevice] 

Device used to perform the test.

Relation describes that: 
[ #has_/domain  :: MedicalTest]
( #has_/name :: is_using_device)
( #has_/range :: MedicalDevice)

