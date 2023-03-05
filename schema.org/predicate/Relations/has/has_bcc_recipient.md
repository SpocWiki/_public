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
title: has_bcc_recipient

linkTitle: has_bcc_recipient
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
- bcc-recipient
- bcc_recipient
- bccRecipient
- has_bcc_recipient
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_bcc_recipient :: ContactPoint, Organization, Person] or 
- [ has_bcc_recipient :: ContactPoint, Organization, Person] 

A sub property of recipient. The recipient blind copied on a message.

Relation describes that: 
[ #has_/domain  :: Message]
( #has_/name :: is_bcc_recipient)
( #has_/range :: ContactPoint, Organization, Person)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: recipient]

[ #has_/sub_properties :: ]

