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
title: has_recipient

linkTitle: has_recipient
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
- recipient
- recipient
- recipient
- has_recipient
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_recipient :: Audience, ContactPoint, Organization, Person] or 
- [ has_recipient :: Audience, ContactPoint, Organization, Person] 

A sub property of participant. The participant who is at the receiving end of the action.

Relation describes that: 
[ #has_/domain  :: AuthorizeAction, CommunicateAction, DonateAction, GiveAction, Message, PayAction, ReturnAction, SendAction, TipAction]
( #has_/name :: is_recipient)
( #has_/range :: Audience, ContactPoint, Organization, Person)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: participant]

[ #has_/sub_properties :: bccRecipient, ccRecipient, toRecipient]
